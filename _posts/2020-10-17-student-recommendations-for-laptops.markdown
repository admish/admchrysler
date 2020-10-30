---
title: "Student Recommendations for Laptops"
layout: post
date: 2020-10-17 12:08
image: /assets/images/markdown.jpg
headerImage: false
hidden: false
tag:
- laptops
- shopping
star: true
category: blog
author: admchrysler
description: Recommendations for students looking to purchase a new laptop
---

I completely understand that a budget is the largest factor when buying a new computer. However, if finances are tight consider using computers that are made available to you for free. Most public libraries have computers that are free to use. Students attending school on a physical campus almost always have multiple options either in the libraries or computer labs. Even if you're not a computer science major, it's work checking if you can use the computers in their department as well. Net Cafes are still available in some places, plus FedEx and UPS stores also have computers available for a fee.

The options available to your budget, are also directly related to your proficincy with

Students purchasing any laptop under $500 is not built to last very long. In my personal experience, students that buy these laptops need to replace them in as little as 2 years. They either fall apart, the user finds out they are too slow making it difficult to use, or they eventually hit a road block where they just are capable of running some software needed for all of their classes.





There are a wide variety of laptops that are available for around $500, and chromebooks for about $300. If your budget is the primary factor for buying a computer, then they may work for you. They are not computers that are built to last though. Their entire focus is around cost. If you have access to a library or a computer lab at a school, you may be much better off using those instead. If you have no choice and need a computer of your own, consider buying a desktop instead.

If you can afford to save up a little more you can purchase a computer.

System Requirements

The [Windows 10 system requirements][1] from Microsoft extremely overzealous. They are the same requirements of 1GHz processor, and 1 GB of RAM, that Microsoft claimed was needed for [Windows Vista][2] in 2006. The realistic truth is you will need at least 4GB of RAM as a bare minimum, but 8GB of RAM to use Windows 10 comfortably.







[1]: https://support.microsoft.com/en-us/windows/windows-10-system-requirements-6d4e9a79-66bf-7950-467c-795cf0386715
[2]: https://web.archive.org/web/20080101144743/http://www.microsoft.com/windows/products/windowsvista/editions/systemrequirements.mspx






---


## What kind of laptop should I buy?
 There are only 3 areas you should look at. The rest are personal preference such as screen size and battery length. Those three areas are the hard drive, the RAM (aka Memory), and the CPU. These areas apply to both Apple and Windows equally.

### Hard Drive:
At a minimum, you should have 250GB of solid-state storage. If possible 500GB or more of storage, but it should be solid state. Mechanical drives do have larger capacities for less money, but they will make your whole computer run much slower. If you are looking to replace an old computer that has a mechanical drive, consider upgrading it to solid state for around $100 and get a couple more years out of it.

### RAM:
8GB will run most everything. More RAM will allow you to have more programs, or web browser tabs, open at once. Anything over 16GB is probably overkill for a laptop unless you are analysis research on it.

### CPU:
The CPU is a little harder to gauge because manufactures will only advertise the clock speed. Try to find the model number and compare the Passmark rating. Higher is better, and anything with a score over 8,000 should stay current for several years.











## Basic formatting

This note **demonstrates** some of what [Markdown][1] is *capable of doing*.

And that's how to do it.

{% highlight html %}
This note **demonstrates** some of what [Markdown][some/link] is *capable of doing*.
{% endhighlight %}

---

## Headings

There are six levels of headings. They correspond with the six levels of HTML headings. You've probably noticed them already in the page. Each level down uses one more hash character. But we are using just 4 of them.

# Headings can be small

## Headings can be small

### Headings can be small

#### Headings can be small

{% highlight raw %}
# Heading
## Heading
### Heading
#### Heading
{% endhighlight %}

---

## Lists

### Ordered list

1. Item 1
2. A second item
3. Number 3

{% highlight raw %}
1. Item 1
2. A second item
3. Number 3
{% endhighlight %}

### Unordered list

* An item
* Another item
* Yet another item
* And there's more...

{% highlight raw %}
* An item
* Another item
* Yet another item
* And there's more...
{% endhighlight %}

---

## Paragraph modifiers

### Quote

> Here is a quote. What this is should be self explanatory. Quotes are automatically indented when they are used.

{% highlight raw %}
> Here is a quote. What this is should be self explanatory.
{% endhighlight raw %}

---

## URLs

URLs can be made in a handful of ways:

* A named link to [Mark It Down][3].
* Another named link to [Mark It Down](https://google.com/)
* Sometimes you just want a URL like <https://google.com/>.

{% highlight raw %}
* A named link to [MarkItDown][3].
* Another named link to [MarkItDown](https://google.com/)
* Sometimes you just want a URL like <https://google.com/>.
{% endhighlight %}

---

## Horizontal rule

A horizontal rule is a line that goes across the middle of the page.
It's sometimes handy for breaking things up.

{% highlight raw %}
---
{% endhighlight %}

---

## Images

Markdown can also contain images. I'll need to add something here sometime.

{% highlight raw %}
![Markdowm Image][/image/url]
{% endhighlight %}

![Markdowm Image][5]

*Figure Caption*?

{% highlight raw %}
![Markdowm Image][/image/url]
<figcaption class="caption">Photo by John Doe</figcaption>
{% endhighlight %}

![Markdowm Image][5]
<figcaption class="caption">Photo by John Doe</figcaption>

*Bigger Images*?

{% highlight raw %}
![Markdowm Image][/image/url]{: class="bigger-image" }
{% endhighlight %}

![Markdowm Image][5]{: class="bigger-image" }

---

## Code

A HTML Example:

{% highlight html %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1>Just a test</h1>
</body>
</html>
{% endhighlight %}

A CSS Example:

{% highlight css %}
pre {
    padding: 10px;
    font-size: .8em;
    white-space: pre;
}

pre, table {
    width: 100%;
}

code, pre, tt {
    font-family: Monaco, Consolas, Inconsolata, monospace, sans-serif;
    background: rgba(0,0,0,.05);
}
{% endhighlight %}

A JS Example:

{% highlight js %}
// Sticky Header
$(window).scroll(function() {

    if ($(window).scrollTop() > 900 && !$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeOut('fast');
    } else if (!$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeIn('fast');
    }

});
{% endhighlight %}

[1]: https://daringfireball.net/projects/markdown/
[2]: https://www.fileformat.info/info/unicode/char/2163/index.htm
[3]: https://daringfireball.net/projects/markdown/basics
[4]: https://daringfireball.net/projects/markdown/syntax
[5]: https://kune.fr/wp-content/uploads/2013/10/ghost-blog.jpg
