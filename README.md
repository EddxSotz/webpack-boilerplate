# webpack-boilerplate
Simple yet powerful webpack boilerplate

Download and copy next files onto your project folder:
<li>/scr</li>
<li>gitignore</li>
<li>webpack.config.js<li>

On VS code terminal run: 
<li>npm init -y</li>
<li>npm install webpack webpack-cli --save-dev</li>
<li>npm install --save-dev html-webpack-plugin</li>
<li>npm install --save-dev style-loader css-loader</li>
<li>npm install --save-dev webpack-dev-server<li>

Tip: When installing a package that will be bundled into the production bundle, you should use npm install --save. If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use npm install --save-dev

Save the following lines inside the package.json file that generated automatically "private": "true",
and inside the scripts include :
<li>"build": "webpack",</li>
<li>"start": "webpack serve --open"</li>

To run webpack enter command:
npm run build

To run live server run: 
npm start