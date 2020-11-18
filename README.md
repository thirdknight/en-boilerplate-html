// Website

- Create index.html or index.php for index.php we need create Folder include/a_config.php

- Check in the Terminal: edinson@Edinsons-MBP gulpv4-sass-browsersync-edi
$ node -v 

- Create project, npm init is going to initialize things within      
  individual project
  $ npm init -y
- Install Gulp Globally: is preferred because it allows you to use different    
  versions of gulp
  $ npm i gulp-cli -g
- Install Gulp as dev dependency(The node_modules will be created)
  npm i gulp -D
- Create gulpfile.js
- Gulps dependencies
  npm i --save-dev gulp-imagemin
  npm i node-sass gulp-sass --save-dev
  npm i --save-dev gulp-sourcemaps gulp-concat gulp-terser
  npm i -D gulp-babel @babel/core @babel/preset-env
  npm i -D gulp-plumber
  npm i -D browser-sync 
  
   


  



- Create package-lock.json and node_moudeles for gulp, sass     
  and browser-sync with: 
  $npm install --save-dev gulp gulp-sass browser-sync //browser-sync work only with index.html    but not with index.php
  
- Create gulpfile.js and copy the script
- run:
   gulp watch

//Frontend
- Add normalize
- Create scss/styles.scss and css/styles.css Folders
- Search icons: Fontastic
- Search fonts: google
- create favicon: https://favicon.io/favicon-generator/
  Background: square, Lemonada, font-size:60
- Search images

root
|- package.json
|- index.html
|- /src
  |- index.js



scss
  |- base
    | _mixin.scs
    | _varibles.scss
    | _typo.scss
  |- components/
    | _base.scss
    | _buttons.scss
    | _layout.scss
    | _nav-menu.scss
  | _normalize.scss
  | _styles.scss 


