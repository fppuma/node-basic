## Npm init & Express
```
$ npm init
```
A file **package.json** will be generated.

Ensure the project uses standard ES6 by adding:
```
"type": "module",
```
in the **package.json** file.

## Installing Express
```
$npm install express
```

- New file: package-lock.json
- New folder: node_modules

## Dev tools
```
npm install --save-dev nodemon
```

## Configure package.json
Adding start
```js
"scripts": {
    "start": "nodemon index.js"
  },
```
## Start the application
```
npm start
```
In the browser
```
http://localhost:3000
```

## Middleware Express
```js
app.use(express.static('static'));
```


