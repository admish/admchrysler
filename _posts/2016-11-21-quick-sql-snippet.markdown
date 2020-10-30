---
title: "Code snippet for creating new SQL"
layout: post
date: 2016-11-21 12:32
image: /assets/images/mysql.png
headerImage: true
hidden: false
tag:
- snippets
- sql
- mysql
- mariadb
category: blog
author: admchrysler
description: Recommended laptops for students during the Fall 2020 Semester
---

Best method for quickly creating a new database and unique user in SQL that is universally compatible with php and cli based applications.

Begin by logging in to MySQL/MariaDB through terminal with `mysql -u root -p`. Do not type password on this line to avoid it being recorded in `.bash_history` file. It will prompt for the password.

* `db_name` : Name of SQL database
* `user_name` : Name of new SQL user that will have full access (limit 32 characters)
* `localhost` : IP address if SQL is on remote server
* `password` : Password for new SQL user (limit 32 characters)

```sql
CREATE DATABASE db_name DEFAULT CHARACTER SET utf8 COLLATE utf8_unicode_ci;
CREATE USER 'user_name'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON db_name.* TO 'user_name'@'localhost';
FLUSH PRIVILEGES;
EXIT;
```