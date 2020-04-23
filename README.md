# Oneline
One line style for Firefox inspired by the Nord color palette and implemented via userChrome.css
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/main_window.png)

## This theme
Insipred by blues of the Nord theme minimal one line design with custom extension themes. If this is your first time trying to style FireFox via userChrome.css start here [Getting Started with userChrome.css and userContent.css](https://github.com/ultrahumanite/oneline#getting-started-with-userchromecss-and-usercontentcss)

### Custom Extension Icons Implementation
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/extension_icons.png)

## Getting Started with userChrome.css and userContent.css
This is the minimum esentail setup you need to go thru in order to use userChrome.css and userContent.css to style Firefox. If you've already enabled userChrome.css support in your Firefox setting and created the chrome folder in your profile folder you can skip this section.

### Enable userChrome.css and userContent.css in FireFox
You must enable userChrome.css and userContent.css functionality in Firefox before creating your custom userChrome.css and userContent.css files. Type **about:config** in your url bar and press Enter search for ***toolkit.legacyUserProfileCustomizations.stylesheets*** and set the value to **true**.

### Locating your profile folder and creating the chrome folder
This is were userChrome.css and userContent.css as well as the custom icon files if you choose to use those.
1. Type about:support in the url bar and press enter
2. In the Application Basics table locate section named Profile Folder and click on Show in Finder
3. Inside your profile folder create a new folder and name it chrome
4. Double click the chrome folder and copy or create userChrome.css and userContent.css files inside it
5. Restart Firefox

**Optional**
The process described below will allow you to edit userChrome.css and userContent.css in real time and imitaitelly see how your edits affect the way Firefox looks.

![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/console.png)
**Setting up FireFox build in Developer Tools for real time userChrome.css and userContent.css editing and previewing.**
1. Pres Cmd + Opt + i a new pannel will open in the Firefox window
2. Click on the three dots that appears in the right top corner of the panel that just opened, next to the x button
3. Scroll down to Advanced Settings and check the settings "Enable browser chrome and add-on debugging toolboxes" and "Enable remote debugging".
4. Close the developer tools panel and proceed with next tutorial

**Using Developer Tools for real time userChrome.css and userContent.css editing and preview.** 
1. Press Cmd + Opt + Shift + i on Mac
2. A permission dialog will prompt you to allow remote debug, clic ok
3. Click on the tab Style Editor, choose file userChrome.css from the sidebar on the left
4. Choose the style you want to preview from this repository, copy the code
5. Scroll down on the development tools window textbox, paste the code 
6. You should see the style being applied. If you like what you see, you can click Save, otherwise it will disappear after restarting the browser.
