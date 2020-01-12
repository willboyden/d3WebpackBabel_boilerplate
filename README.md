# d3WebpackBabel_boilerplate
empty project initialized with d3, Webpack, and Babel. 
with these commands the only thing that should need to be modified is the package.json file
in the package.json file add the 2lines below to "scripts" <br/>
"webpack-dev-server": "webpack-dev-server",<br/>
"webpack": "webpack"


#powershell commends used

npm init -y

npm i --save-dev @babel/core webpack webpack-cli webpack-dev-server http-server babel-loader

npm i d3

#builds project
npm run webpack

#runs with development web server
npm run webpack-dev-server
