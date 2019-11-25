Ciklum University: JS Band Internship. Homework task 4

## This application is desktop version for delivery companies.

The main goal what the app improved it collect information about transport and delivery cost.
User's data stored in localStorage.

## Implemented tasks:
* add eslint 
* add commitizen 
* configured webpack for development/production mode and common for both 
* add tests (Jest)


## Description scripts: 
```npm run dev```

Run application in the development mode. After that in browser automaticly open page **localhost:8080**

```npm run build``` 

Run application in the production mode. After that in the main directory of project would be create folder  **build** (files for production)

```npm run eslint```

Run linter (airbnb) 

```npm run eslint-fix```

Run linter with key --fix for fix code (if needed)

```npm run test```

Run Jest tests 

```npm run commit```

This script should be use after ```git add```, it standardization commit 

```npm run deploy```

Deploying a project on gh-pages (should use after ```npm run build``` or ```npm run predeploy```)

## Project Structure
```
├── jest
│   └── test.js
│ 
├── style
│   └── style.css
│
├── public
│   └── index.html
│
├── webpack
|    ├── webpack.common.js
|    ├── webpack.prod.js
|    └── webpack.dev.js
|
├── js
|   ├── index.js
|   ├── render.js
|   ├── constats
|   |   └── common.constats.js
|   ├── createforms
|   |   ├── cost.js
|   |   └── transport.js
|   ├── helpers
|   |   └── makeid.js
|   ├── models
|   |   ├── сostofdelivery.js
|   |   ├── ship.js
|   |   ├── transport-factory.js
|   |   ├── transport.js
|   |   └── truck.js
|   ├── services
|   |   └── localstorage.js
|   └── templates
|       ├── cost-form.js
|       ├── cost-item.js
|       ├── transport-form.js
|       └── transport-item.js
```