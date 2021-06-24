---
permalink: /ytguide.html
description: How to use programs to record VTuber streams from the beginning
---

# How to use record VTuber streams from the beginning

So you're an archiver but don't really have a way to record (often unarchived) ⛩️ streams from youtube-dl unless jumped in from the very start. Look no further to this shitty guide.   
This guide will cover how to install programs such as [ytarchive](https://github.com/Kethsar/ytarchive), which that will record streams from the very beginning without having to be on the stream from the start time. 

This guide assumes you have [ffmpeg](https://www.ffmpeg.org/) installed.

How in install on platform:
* []
* [MacOS/Unix](#ytarchive-on-macos)

# ytarchive on Windows    
to be written later lol   

# ytarchive on MacOS   

＊This should apply to Unix systems as well.    
Because it isn't really detailed on the repo page:

1. Open Terminal (or some other commandline program you have)   
2. Type `git clone https://github.com/Kethsar/ytarchive.git` to get the script on your computer   

You're technically done installing now. For regular usage:   

1. Type `cd ytarchive` in Terminal   
2. Type `python3 ytarchive.py -w [link] 1080p60/best`   

It will then start recording from the beginning. Things such as mismatched frames are bound to happen at first time use so it isn't completely fool-proof. 
