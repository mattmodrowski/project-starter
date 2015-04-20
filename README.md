#project-starter

project-starter is a base template for starting and executing your web development workflow. It includes a basic directory structure, a starter index.html file, and Gulp tasks to optimize styles, scripts, and images.

##Usage
###Install Node packages
`npm install`

###Run Gulp
`gulp`

##Optimizing Images
`gulp images`

##Styles Structure
###/screen.scss
This includes a reference to all of your scss partials.

###/base/
The base folder includes normalize.scss to force browsers to render elements more consistently, variables.scss to contain all your Sass variables, and global.scss for global styles like paragraphs, lists, etc.

###/components/
The components folder is for reusable components like headers, footers, etc.

###/layouts/
The layouts folder is for larger layout customization like the main page vs. internal articles, for example.

###/plugins/
The plugins folder contains any additional third-party CSS.