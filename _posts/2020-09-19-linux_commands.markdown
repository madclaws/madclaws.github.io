---
layout: post
title:  "Handy linux commands for me"
date:   2020-09-19 07:14:00 +0530
categories: jekyll update
---
<h2><b>Some handy linux commands reference</b> </h2>
<h4><b>Info about the process running on a port</b></h4>
   ``` lsof -i :<PORT> ```
<h4><b>Location of the running process</b></h4>
  ``` lsof -p <PID> | grep cwd ```
<h4><b>Killing a process</b></h4>
  ``` kill <PID> ```
<h4><b>Copying a folder</b></h4>
  ``` cp -avr /tmp/conf/ /tmp/backup/ ```
<h4><b>Removing files older than X days</b></h4>
  ``` find <path>/*.log -mtime +X -exec rm {} \;  ```

[jekyll-gh]:   https://github.com/madclaws
