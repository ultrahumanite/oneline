# Oneline
One line style for Firefox inspired by the [Nord](https://www.nordtheme.com/) color palette and implemented via userChrome.css
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/main_window.png)

## This theme
Insipred by blues of the Nord theme minimal one line design with custom extension themes. If this is your first time trying to style FireFox via userChrome.css start here [Getting Started with userChrome.css and userContent.css](https://github.com/ultrahumanite/oneline#getting-started-with-userchromecss-and-usercontentcss) otherwise to install copy the userChrome.css and userContent.css to your chrome folder, also cosult [Custom extension icons](https://github.com/ultrahumanite/oneline#custom-extension-icons) below if your want to use your own icons.

**Note:** This is a best effort project the code is messy and might include redundnat elements, I welcome all help and input directed toward improving it.
 
### Custom extension icons
The process described below will allow you to substitute the defualt icons of your extensions. Reffer to the below screenshots and follow the setp-by-step instructions. 
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/custom_icons.png)
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/icons_console.png)
1. Press Cmd + Opt + Shift + i to bring up the Developer Tools window
2. Locate the element picker in the top left corner of the Developer Tools window, select it
3. Hoover the mouse cursor over the extension icon you want to replace and click on it
4. Reffer back to the Developer Tools window and locate a highlited block of code begining with ```<toolbarbutton id="``` copy the id value located between the quotation marks (example ```<toolbarbutton id="ublock0_raymondhill_net-browser-action"``` copy ```ublock0_raymondhill_net-browser-action"```)
5. Make a new entry in you userChrome.css file using the example below. Replace ublock0_raymondhill_net-browser-action with your own id value you have copied in the step 4 and replace the ads.png with the name of the image you want to use
```css
#ublock0_raymondhill_net-browser-action {
  list-style-image: url("ads.png") !important;
}
```
6. Copy the the image file you want to use to your chrome folder
**Note:** A good source of free replacment icons: ![Flaticons](https://www.flaticon.com)

## Getting started with userChrome.css and userContent.css
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

**Setting up FireFox build in Developer Tools for real time userChrome.css and userContent.css editing and previewing**
Reffer to the below screenshot and follow the setp-by-step instructions.
![alt text](https://raw.githubusercontent.com/ultrahumanite/oneline/master/screenshots/console_one.png)
1. Pres Cmd + Opt + i a new pannel will open in the Firefox window
2. Click on the three dots that appears in the right top corner of the panel that just opened, next to the x button
3. Scroll down to Advanced Settings and check the settings "Enable browser chrome and add-on debugging toolboxes" and "Enable remote debugging".
4. Close the developer tools panel and proceed with next tutorial

**Using Developer Tools for real time userChrome.css and userContent.css editing and preview**
Reffer to the below screenshot and follow the setp-by-step instructions.
1. Press Cmd + Opt + Shift + i on Mac
2. A permission dialog will prompt you to allow remote debug, clic ok
3. Click on the tab Style Editor, choose file userChrome.css from the sidebar on the left
4. Choose the style you want to preview from this repository, copy the code
5. Scroll down on the development tools window textbox, paste the code 
6. You should see the style being applied. If you like what you see, you can click Save, otherwise it will disappear after restarting the browser.

## Credits and resources
This theme has been made possible by the good people of [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/) majority of the code comes from the users of this great sub-reddit.
