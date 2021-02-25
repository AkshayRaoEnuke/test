# Mindpeers

## Installation and Setup Instructions

#### Example:  

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  

Installation:

`npm install`  

To Start Server:

`npm start`  

To Visit App:

`localhost:3000/`  
## Folder Structure

After creation, your project should look like this:

```
my-app/
  README.md
  node_modules/
  package.json
  public/
    css/
    fonts/
    img/
    js/
  src/
    components/
    pages/
    routers/
    store/
    utils/
    

```
## About Public Folder
For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template

You can delete or rename the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Babel.<br>
You need to **put any JS and CSS files inside `src`**, or Babel won’t see them.

Only files inside `public` can be used from `public/index.html`.<br>
Read instructions below for using assets from JavaScript and HTML.

The public folder contains the HTML file so you can tweak it, for example, to set the page title. 
The css,fonts,img and scripts with the compiled code will be added to it automatically during the build process.

Favicon in public folder <br>
The favicon is an icon that is used in your application as its logo. they are often found, 
for example, on browser tabs or as a logo on your desktop or smart home screen.

**Adding Assets Outside of the Module System <br>**
You can also add other assets to the public folder.

Note that we normally encourage you to import assets in JavaScript files instead. For example, see the sections on adding a stylesheet and adding images and fonts. This mechanism provides a number of benefits:

* Scripts and stylesheets get minified and bundled together to avoid extra network requests.
* Missing files cause compilation errors instead of 404 errors for your users.
* Result filenames include content hashes so you don’t need to worry about browsers caching their old versions.

## About src Folder

Our src folder is major folder which it contains all our react project code base.
In src folder we have,
 * Components
 * Pages
 * routers
 * store
 * utlis
## Components Folder
* Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
* Components folder holds  components of each page .
* Each page components has splited accordingly to folders.
* For example In subcomponent folder we have  Therapy Folder contains all the therpay page componenets.
* There are common folder which helps to store Common components which can be accessible to all pages.
## Pages Folder
* pages is the JavaScript entry point for every Componenet of the page.
* This acts as a container for all components respective to their pages.
* here for each page there is separate folder created.
* For example Selfcare Page , we have seprate folder pages->SelfCare->SelfCare.js is present.
## Routers Folder
* React Router is a standard library for routing in React. 
* It enables the navigation among views of various components in a React Application, allows changing the browser URL, and keeps the UI in sync with the URL.
