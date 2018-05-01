# Steps
1.   Install node-sass, compilator de sass/scss

 > npm install -g sass

 2.  Create a package.json

> npm init

3. Define a task to compile - add following into the scripts 

>  "build-scss": "node-sass --include-path scss src/scss/main.scss   src/main.css"

4. Run the task 

> npm run build-scsss

5. Use inheritance sample code from [ sass documentation ](https://sass-lang.com/guide) for messages classes