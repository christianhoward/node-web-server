# node-web-server
This is my web server project following [Andrew Mead](http://www.mead.io/)'s Complete Node.js Developer Course on Udemy. This repo is used purely for learning exercises and the course content should not be interpreted as something I've created on my own.

The web server project uses the Express framework and Handlebars templating language to run basic static routes on a website. Node.js' File System is used to create a server log. This project is hosted on [Heroku](https://vast-plains-97868.herokuapp.com/) if you are interested in testing it out.

## Routes
There are four routes set up in this project.

### /
The `/` route renders a home page that uses the home.hbs Handlebars file along with the header.hbs and footer.hbs partial files.

### /about
The `/about` route renders an about page that uses the about.hbs Handlebars file along with the header.hbs and footer.hbs partial files.

### /projects
The `/projects` directory renders a projects page that uses the projects.hbs Handlebars file along with the header.hbs and footer.hbs partial files.

### /bad
The `/bad` route returns an error message that the request could not be fulfilled.
