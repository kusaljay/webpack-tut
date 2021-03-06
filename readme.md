# Install & Configure webpack step-by-step

### 1. Create a default package.json
```bash
npm init -y
```

### 2. Install webpack
```bash
npm i -D webpack webpack-cli
```

### 3. Install Babel and Babel loader
```bash
npm i -D babel-loader @babel/core @babel/preset-env
```
*Check webpack.config.js* 

### 4. Install Webpack-dev-server
```bash
npm i -D webpack-dev-server
```
*Check package.json*

### 5. Install HTML webpack plugin and HTML loader
```bash
npm i -D html-webpack-plugin html-loader
```
*Check webpack.config.js*

### 6. Install file loader for images
```bash
npm i -D file-loader
```
*Check webpack.config.js*

### 7. Install support for SASS and loaders
```bash
npm i -D node-sass style-loader css-loader sass-loader mini-css-extract-plugin
```