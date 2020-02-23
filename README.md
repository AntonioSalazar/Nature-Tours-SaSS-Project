Project created for learning purposes.

Tried a lot of SaSS cool stuff :)

For you to be able to see the project you just need to open the index.html file

If you want to clone the repository run the 'npm install' command, this will only add the 'node-sass' package that is used as a dev dependencie.

And the 'npm run compile:sass"

This command will run the next script from the package.json:

"scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css -w"
}

This adds the changes from sass files into the style.css file.

Some screenshot of the project -->

![](img/home.png)


If you click on the menu icon the next options will be displayed:

![](img/menu.png)
