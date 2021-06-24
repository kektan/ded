---
permalink: /ytguide.html
description: How to use programs to record VTuber streams from the beginning
---

# How to use record VTuber streams from the beginning

So you're an archiver but don't really have a way to record (often unarchived) ⛩️ streams from youtube-dl unless jumped in from the very start. Look no further to this shitty guide.   
This guide will cover how to install programs such as [ytarchive](https://github.com/Kethsar/ytarchive), which that will record streams from the very beginning without having to be on the stream from the start time. 

This guide assumes you have [ffmpeg](https://www.ffmpeg.org/) installed.

How in install on platform:
* [Windows](#ytarchive-on-windows)
* [MacOS/Unix](#ytarchive-on-macos)

# ytarchive on Windows    
1. Download the latest release on the github page. (Maybe preferably the .zip file)    
2. Extract the zip file.    
3. Run ytarchive.exe    
4. Input the link to a(n ongoing) stream when prompted. Input quality as `1080p60` or `best` when prompted.    

dun dun dun dun you did it ✨    
for regular usage, repeat 3 and 4.    

# ytarchive on MacOS   

＊This should apply to Unix systems as well.    
Because it isn't really detailed on the repo page:

1. Open Terminal (or some other commandline program you have)   
2. Type `git clone https://github.com/Kethsar/ytarchive.git` to get the script on your computer   

You're technically done installing now. For regular usage:   

1. Type `cd ytarchive` in Terminal   
2. Type `python3 ytarchive.py -w [link] 1080p60/best`   

It will then start recording from the beginning. Things such as mismatched frames are bound to happen at first time use so it isn't completely fool-proof. 

### Passing cookies
In the very case of an unarchived member-only stream, you can pass cookies with `-c [cookies.txt file]`   

1. Get an extension like [Get cookies.txt](https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid/) (Chrome) or [cookies.txt](https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/) (Firefox)   
2. Go to YouTube homepage with the account you have access to memberships to, then click on the extension to extract the cookies.
3. Save the cookies.txt file somewhere you have easy access to them, like on Desktop or something
4. If you're using ytarchive to record membership streams, type `-c ` then drag and drop the cookies.txt file you extracted. (It's easier that way.)
