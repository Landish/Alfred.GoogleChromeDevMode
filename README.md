#Alfred Google Chrome Developer Mode
[Alfred App](http://www.alfredapp.com/) Extension to open [Google Chrome](https://google.com/chrome) with disabled Web Security.

#Requirements
* [MAC](http://www.apple.com/mac/)
* [Alfred App](http://www.alfredapp.com/)
* Being a Web-Developer

#What it does?
As a Web-Developer I often make AJAX calls from localhost to remote server. This can be very painful with Google Chrome, because it blocks requests with enabled web securtiy mode. So, I've made a simple extension to solve this problem.

#Usage

1. Download [latest zip file](https://github.com/Landish/Alfred.GoogleChromeDevMode/archive/master.zip) on your computer and unzip it.
2. Open **Alfred App Preferences** and switch to "**Workflows**" tab.
3. Drag "**GoogleChromeDevMode.alfredworkflow**" file from downloaded archive and drop it to left sidebar.
4. Type "**dws**" (stands for "Disable Web Security") on Alfred window to open Google Chrome with disabled Web Security. 

#Manual Mode
If you don't want use this extension and just want to open Google Chrome with disabled Web Security, then just run the following command in **Terminal**:
```
open -a Google\ Chrome --args --disable-web-security
```

#Images
![Alfred Google Chrome Developer Mode](https://raw.github.com/Landish/Alfred.GoogleChromeDevMode/master/images/preview.jpg)