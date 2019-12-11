# Employee Directory

This app displays the employee directory for a fictional company called Awesome Startup. 

The content is generated by connecting to the [randomuser.me](https://randomuser.me/) API.

The app allows for employee name search and a full detail view in a modal that can be toggle back and forward.

## Required Technology

Interned connection along with a server is needed for the API to run correctly.

## How To Use

Clone and upload the file to a server or run it locally. Open the index.html to view the file.

If you have [browsersync.io](https://www.browsersync.io/) already installed, you can run locally using:

```
browser-sync start --server --files "css/*.css"
```

## Style Updates

CSS styles were provided at the start of the project, but was requested to add additional styles to improve the look of the application without affection the layout. Bellow are the additional changes I've made:

 - Updated font to Open Sans for better legibility
 - Removed borders that made the app look outdated
 - Set a standard border radius of 6px
 - Changed to brighter colours
 - Added a darker background behind the cards for better readability
 - Added hover effect for cards
 - Styled scrollbars to match the app design
 - Adjusted space around the modal
 - Changed hr styles for something cleaner
 - Updated button styles to match the app
 - Added a blur effect for chrome
 - Added animations for presenting the modal
 - Added proper links for email and phone inside modal

### Before & After
![Before](mockups/employee_directory.png)
![After](mockups/employee_directory_after.png)
![Before](mockups/employee_overlay.png)
![After](mockups/employee_overlay_after.png)