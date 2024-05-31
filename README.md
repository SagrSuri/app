# How to deploy vite react website

- After Complete your Project run below command on your terminal (make sure you are on our project directory terminal)
- ``` npm install gh-pages --save-dev ```
- open package.json file --> add on top of name --> ``` "homepage": "https://yourusername.github.io/yourrepository/", ```
- in package.json two script add--> ``` "predeploy": "npm run build",
    "deploy": "gh-pages -d dist", ```
- open your vite.config.js file --> add--> ``` base: "/reponame/", ```

- Now add our project on GITHUB REPO 

- done--> ``` npm run deploy ```

- [Youtube-Video](https://youtube.com/@sagrsuri)
