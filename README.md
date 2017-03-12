# ReactReduxActivityCounter
React, Redux activity counter.

## Install the following extensions in your browser (i.e. Chrome/Firefox):
+ React-detector
+ react-developer-tools

```
sudo npm install -g httpster
httpster -d ./dist -p 3000
```
After converting to JSX we will need to use [babel](https://babeljs.io/) to
transpile the JSX.

Use Babel's in browser transpiler [cdnjs.com babel 5.8.38](https://cdnjs.com/libraries/babel-core/5.8.38)

```
# create .babelrc file
$ npm install --save-dev babel-preset-latest babel-preset-react babel-preset-stage-0
$ npm i webpack babel-loader webpack-dev-server --save-dev
$ sudo npm i -g webpack
$ webpack
$ node -v
v6.9.1  
$ npm -v
3.10.8
$ # get lattest from https://nodejs.org/en/
$ node -v
v6.10.0
$ npm -v
3.10.10
$
npm i --save react react-dom
npm i --save-dev json-loader

npm i style-loader css-loader autoprefixer-loader sass-loader node-sass --save-dev
# Note: npm WARN deprecated autoprefixer-loader@3.2.0: Please use postcss-loader instead of autoprefixer-loader
#       npm WARN prefer global node-gyp@3.5.0 should be installed with -g

# Add configuration for each of the above loaders to the webpack.config.js file.
```
+ [React icons](https://gorangajic.github.io/react-icons/fa.html)
```
npm i --save react-icons
```
+ The use of propTypes is vary useful for validation and aids in the debugging processes. [React.propTypes](https://facebook.github.io/react/docs/typechecking-with-proptypes.html)
