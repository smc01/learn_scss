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

# Documentation

[Css preprocessors](https://htmlmag.com/article/an-introduction-to-css-preprocessors-sass-less-stylus)

[Less documentation](http://lesscss.org/)

[sass documentation](https://sass-lang.com/)

[sass vs Less](https://css-tricks.com/sass-vs-less/)

[sass vs Less2](https://gist.github.com/chriseppstein/674726)

[sass and scss](https://stackoverflow.com/questions/5654447/whats-the-difference-between-scss-and-sass)



