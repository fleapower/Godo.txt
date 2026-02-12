# Godo.txt #
### Google Apps Script for todo.txt. ###

**Disclaimer: Back up your todo.txt file or just create a new one before testing! If you fail to back up your file, you can always recover it using the file versioning on Google Drive. Use at your own risk!**

This is a GAS web app implementation of todo.txt. To deploy the script:
1) Go to https://script.google.com (you will need a Google account).
2) Create three files: code.gs, index.html, and help.html.
3) Cut and paste the code from the three files with those names contained in this repository into the correct files you just created.
4) Click _Deploy -> New Deployment_.
5) Click the gear and select Web App.
6) Description can be anything you want.
7) Execute as Me (leave this unless you know what you are doing and understand the risks).
8) Access should be yourself (leave this unless you know what you are doing and understand the risks).
9) Click _Authorize Access_ and follow the prompts.
10) When the _New deployment_ window comes up, copy the Web app URL. Click _Done_.
11) Open a new window and paste the URL you just copied.

The GAS should be running as a web app. The first thing you should do is click the _Load ToDo.txt file_.

![godo sample](https://github.com/user-attachments/assets/8ce98e7c-a1b0-420b-b82c-d57676da9e40)

<ins>**Change Log**</ins>

<ins>2.0</ins>  
NEW: Implemented drag and drop  
CHANGE: Changed some hotkeys for better user experience  
BUG FIX: Hang when selecting bulk action after using CTRL-A  
BUG FIX: Fixed autosave not triggering after drag and drop  

<ins>1.0</ins>  
Initial release.
