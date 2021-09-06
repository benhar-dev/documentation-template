# Example documentation project

## Overview
It is often a requirement to include documentation with your software project.  This repo can act as a startin point for your work.  Simply replace or edit this readme with your project front sheet, add your code to the src folder, then enable github pages to serve your docs folder.  

The documentation that this repo produces is here! [See your documentation](https://benhar-dev.github.io/documentation-template/)

Information on Github pages can be found [here](https://pages.github.com/)...

## Editing Guide
It is not a requirement to have docsify in order to edit this documentation although it will allow you to preview it offline with its full styling.  

### First time
It is recommended to install docsify-cli globally, which helps initializing and previewing the website locally.
```
npm i docsify-cli -g
```

### Live preview
You will now be able to preview the site locally by running the following command in the root of the repo.
```
npm start
```
All changes will cause the live preview to refresh.

### Folder structure
```
.
+-- README.md               || This file
+-- .gitignore              
+-- package.json
+-- package-lock.json
+-- src                     || code goes here 
+-- docs
|   +-- README.md           || This is the main documentation file you will edit
|   +-- index.html          || Docsify template html
|   +-- .nojekyll           || Tells Github to bypass Jekyll on GitHub Pages
|   +-- docsify
|       +-- custom.css      || Custom styling away from the docsify standard
|       +-- language-st.css || Structured text syntax highlighting
|       +-- language-st.js  || Structured text syntax highlighting
|       +-- plugins         || Plugins to docsify go here...
```