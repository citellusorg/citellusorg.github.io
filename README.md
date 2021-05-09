## README

If you want to contribute to citellusorg.github.io with a blog entry, please do create a new PR to this repo (on the `source` branch) , which contains a new file (markdown) in the contents/ folder.

Use one of the prior files as a template and ensure to use DATE-title.md as filename and update the relevant tags inside the file, such as:

~~~
---
layout: post
title: Recent changes in Magui and Citellus
date: 2018-05-08 7:17:00 +0200
comments: true
tags: citellus, magui, whatsnew
category: blog
description:
---
~~~

The file, once merged, will be use to regenerate the web with pelican (static html generator based in python) and published to the master branch.

The steps, would be something like:

~~~sh
git clone https://github.com/citellusorg/citellusorg.github.io.git
git checkout source
edit file at content/YEAR-MONTH-DAY-title.md
git add content/YEAR-MONTH-DAY-title.md
git commit -m "your commit message"
git push
~~~

Contact us at #citellus in Freenode if in need of help
