# Finch Pro 2 - Fullstack
  -Live Site URL: [https://jul-lactao.netlify.app/](https://jul-lactao.netlify.app/)
  
  
## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Creating a Github Repository](#repo)
  - [Install Dependencies](#dependencies)
  - [Additional Info](#additional-info)
  - [Built With](#built-with)
- [Author](#author)

## Overview

### Screenshot

![](./_readme_img/portfolio.png)

### Links

  -Live Site URL: [https://jul-lactao.netlify.app/](https://jul-lactao.netlify.app/)

## Creating a Github Repository
1.  **Delete .git inside client folder to avoid errors during pushing**
1.  **Git init**

    Navigate into your new site’s main directory and then git init.

    ```shell
    cd ..
    git init
    ```

1.  **Create a new repository in the github website**
1.  **Go back to VScode and start pushing**

    ```shell
    git add .
    git commit -m "first commit"
    git remote add origin
    git remote add origin https://github.com/julfinch/finch-pro-fullstack.git
    git push origin master
    ```

---
### Install Dependencies

```js
  "dependencies": {
    "@emotion/react": "^11.10.5",
    "@emotion/styled": "^11.10.5",
    "@mui/icons-material": "^5.11.0",
    "@mui/material": "^5.11.0",
    "@mui/x-data-grid": "^5.17.16",
    "@nivo/bar": "^0.80.0",
    "@nivo/core": "^0.80.0",
    "@nivo/geo": "^0.80.0",
    "@nivo/line": "^0.80.0",
    "@nivo/pie": "^0.80.0",
    "@reduxjs/toolkit": "^1.9.1",
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "react": "^18.2.0",
    "react-datepicker": "^4.8.0",
    "react-dom": "^18.2.0",
    "react-redux": "^8.0.5",
    "react-router-dom": "^6.5.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  },
```


---
### Additional Info

**CREATE jsconfig.json**
```js
{
    "compilerOptions": {
        "baseUrl": "src"
    },
    "include": ["src"]
}
```

**CREATE .env.local**
```js
REACT_APP_BASE_URL=http://localhost:5001
```

**IGNORE .env.local and npm modules inside .gitignore**

```shell
    # See https://help.github.com/articles/ignoring-files/ for more about ignoring files.

    # dependencies
    /node_modules
    /.pnp
    .pnp.js

    # testing
    /coverage

    # production
    /build

    # misc
    .DS_Store
    .env.local
    .env.development.local
    .env.test.local
    .env.production.local

    npm-debug.log*
    yarn-debug.log*
    yarn-error.log*

```

### Built with

- Create-React-App
- Material UI
- ReactJS
- Nivo
- Redux-Toolkit

---
 
## Author

- Twitter - [@julfinch](https://www.twitter.com/julfinch)
