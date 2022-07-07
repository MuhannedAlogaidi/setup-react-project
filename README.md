# setup-react-project
# Step 1 : setting-up empty project
# command : npm init . if  you added -y , then the setup will be headless mode and answer all the questions

# Step 2 : setting-up Webpack and CLI 
# command : npm install --save-dev webpack webpack-cli

# Step 3 : Create src directory and index.js file 
# command : mkdire src
# command : cd src touch  index

# Step 4 : Add start and build script in package.json
# command : "start":"webpack --mode development"
# command : "build":"webpack --mode production"

**** Test with node dist/main.js ****  Done!

# Step 5 : Configure webpack to work with React
# command : npm install react react-dom
# command : npm install --save-dev @babel/core babel-loader @babel/preset-env @babel/preset-react
# command : touch babel.config.json
# command : touch webpack.config.js

# confige : Add the configuration for each file
