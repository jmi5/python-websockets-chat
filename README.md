# Python Websockets Example: Chat

This is a simple application that serves tasty WebSockets to your users
with Flask, Flask-Sockets, Gevent, and Gunicorn.

Check out the [live demo](http://flask-chat.herokuapp.com) or [read the docs](https://devcenter.heroku.com/articles/python-websockets).

#### Notes

- To set the `origin` url from the `heroku-examples` repo to mine, I ran `git remote set-url origin <MY_URL>`
- To see what apps were running in Heroku I ran `heroku _`. I saw that I needed to create a new app for this websockets chat platform, and I ran `heroku create`. Once I had the app name from that heroku create process, I ran `heroku addons:create heroku-redis:hobby-dev` which added a Redis db to my app. 

#### Helpful Links 

_Some links I referred to while making this_

- https://help.github.com/articles/changing-a-remote-s-url/
- https://elements.heroku.com/addons/heroku-redis
- http://flask.pocoo.org/docs/0.12/patterns/jquery/
- https://devcenter.heroku.com/articles/python-websockets
- Redis configurations -- REDIS_URL -- https://devcenter.heroku.com/articles/heroku-redis



