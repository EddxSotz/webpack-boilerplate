# webpack-boilerplate
Simple yet powerful webpack boilerplate

Download and copy next files onto your project folder:
/scr
gitignore
webpack.config.js

On VS code terminal run: 
npm init -y
npm install webpack webpack-cli --save-dev
npm install --save-dev html-webpack-plugin
npm install --save-dev style-loader css-loader
npm install --save-dev webpack-dev-server

Tip: When installing a package that will be bundled into the production bundle, you should use npm install --save. If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use npm install --save-dev

Save the following lines inside thepackage.json file that generated automatically "private": "true",
and inside the scripts include :
"build": "webpack",
"start": "webpack serve --open"

