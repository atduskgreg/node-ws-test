# Node.js Websocket Test

A tiny demo using the [einaros/ws](http://einaros.github.io/ws/) WebSockets implementation. Try it [here](https://node-ws-test.herokuapp.com/).

# Running Locally

``` bash
npm install
foreman start
```

# Running on Heroku

``` bash
heroku create
heroku labs:enable websockets
git push heroku master
heroku open
```
