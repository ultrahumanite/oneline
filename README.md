# Oneline
One line sytle Nord theme for Firefox implemented via userChrome.css
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/main_window.png)
## Getting Started with userChrome.css and userContent.css
This is the bare minimum esentail setup you need to go thru in order to use userChrome.css and userContent.css to style Firefox. If you've already enabled userChrome.css and userContent.css in your Firefox setting and created the chrome folder in your profile folder you can skip this section.

### Enable userChrome.css and userContent.css in FireFox
You must enable userChrome.css and userContent.css functionality in Firefox before creating your custom userChrome.css and userContent.css files. Type **about:config** in your url bar and press Enter search for ***toolkit.legacyUserProfileCustomizations.stylesheets*** and set the value to **true**.

### Locating your profile folder and creating the chrome folder
1.
2.
3.
This is were userChrome.css and userContent.css as well as the custom icon files if you choose to use those.

#### Optional
The process described below will allow you to edit userChrome.css and userContent.css in real time and imitaitelly see how your edits affect the way Firefox looks. 

**Setting up FireFox build in Developer Tools for live userChrome.css and userContent.css editing and previewing.** 
1. Pres Cmd + Opt + I
2. Click on the cog that appears in a right or left top corner, next to other buttons.
3. Scroll down to Advanced Settings and check the settings "Enable browser chrome and add-on debugging toolboxes" and "Enable remote debugging".
4. Close the developer tools panel and proceed with next tutorial

**Using Developer Tools for live userChrome.css and userContent.css editing and preview.** 
1. Press Cmd + Opt + Shift + I on Mac
2. A permission dialog will prompt you to allow remote debug, accept
3. Click on the tab Style Editor, choose file userChrome.css on the sidebar
4. Choose the style you want to preview from this repository, copy the code
5. Scroll down on the development tools window textbox, paste the code 
6. You should see the style being applied. If you like what you see, you can click Save, otherwise it will disappear after restarting the browser.

### Custom Extension Icons Implementation
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/extension_icons.png)
