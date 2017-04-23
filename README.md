todo-mean-auth-starter
=====

I was impressed with ui-router-extras and state vis;

This repository adds ui-router-extras, todo to "mean-auth-starter";

> Authentication: Built with the MEAN stack. (JWT, not passport)


### Getting started
```
$ git clone <this_repo_url>
$ cd todo-mean-auth-starter
$ npm install
$ nodemon server
```

### Deploy to Heroku
```
heroku create <app_name>
heroku config:set NODE_ENV=production
heroku addons:create mongolab:sandbox 
heroku config | grep MONGOLAB_URI
git push heroku master
heroku ps:scale web=1
```
