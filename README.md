# Testing bundlers

1. ### Webpack
`npx webpack` it will create file with `main.js` by taking input from `index.js`

2. ### Rollup
`rollup src/index.js --file rollup.js --format iife/cjs` it will create file with `rollup.js` by taking input from `index.js`

3. ### Browserify
`browserify src/index.js -o browserify.js` it will create file with `browserify.js` by taking input from `index.js`

4. ### Parcel
`npx parcel build` update the `package.json` for file names


Now simply replace the `index.html` script tag with appropriate.


#### Links
https://unpkg.com/lodash@4.17.20
https://webpack.js.org/guides/getting-started/
