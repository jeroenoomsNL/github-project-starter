# Github Project Starter
A boilerplate for Github projects to save time on creating a build process and a demo pages for Github Pages.

## Features
-	Build process with [Gulp](http://gulpjs.com) for html, css, javascript and images
-	Deploy task for [Github Pages](https://pages.github.com)
-	Pretty styled and customizable demo page with [initialize.css](http://jeroenoomsnl.github.io/initialize-css/)
-	And lots of best practices

## Easy installation with Yeoman!

First, install [Yeoman](http://yeoman.io) and generator-github-project-starter using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-github-project-starter
```

Then generate your new project:

```bash
yo github-project-starter
```

## Build your project

Build with Gulp
`gulp`

Watch locally (starts browser with browserSync)
`gulp watch`

Deploy to Github Pages
`gulp deploy`
or
`gulp deploy --message 'My first commit'`  


