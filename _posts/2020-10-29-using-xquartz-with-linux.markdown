---
title: "Using XQuartz with Linux"
layout: post
date: 2020-10-29 19:04
image: /assets/images/X11app.png
headerImage: false
hidden: false
tag:
- macos
- linux
- terminal
- xquartz
- ssh
category: blog
author: admchrysler
description: How to remotely use Linux GUI apps on macOS
---

## Installing XQuartz

Complete all of these steps on your own Mac. NOT on the remote machine.

1. Install the latest version of [XQuartz](https://www.xquartz.org/)
2. Edit the file `~/.ssh/config` and add the line
  `XAuthLocation /opt/X11/bin/xauth`
3. Run the command: 
  `defaults write org.macosforge.xquartz.X11 enable_iglx -bool true`
4. SSH into the machine using -X (e.g. `ssh -X user@192.168.0.1`)
5. Type the terminal command to the GUI application


XQuartz is also available through homebrew, but it is not always up to date with the latest version available. It is recommended to download the installer from the official [XQuartz](https://www.xquartz.org/) website.

## Troubleshooting Common Errors
### SSH is looking for xauth in the wrong path.
Seen with the error: **"Warning: untrusted X11 forwarding setup failed: xauth key data not generated"**

This occurs when ssh is looking for xauth in `/usr/X11R6/bin` but on macOS with XQuartz it is located in `/opt/X11/bin`. 
To set the correct path edit the `~/.ssh/config` file on your own computer, and add the following line 
  `XAuthLocation /opt/X11/bin/xauth`

Do not use `ssh -Y` to bypass this error. This uses fake xauth information instead of establishing a secure session.

---- 
### XQuartz is allowing indirect GLX contexts
Seen with the error: **"XRequest.149: BadValue (integer parameter out of range for operation) 0x0 ERROR) Could not create OpenGL rendering context-> Exiting..."**

Completely exit out of XQuartz. In terminal on your local macOS system run the following command:

`defaults write org.macosforge.xquartz.X11 enable_iglx -bool true`

Reload or exit terminal on your local machine, then try logging in again with the `-X` parameter. 

