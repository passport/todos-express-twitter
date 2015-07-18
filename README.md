This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using Twitter.  Use
this example as a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:passport/express-4.x-twitter-example.git
$ cd express-4.x-twitter-example
$ npm install
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access Twitter's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ CONSUMER_KEY=__TWITTER_CONSUMER_KEY__ CONSUMER_SECRET=__TWITTER_CONSUMER_SECRET__ node server.js
```

Open a web browser and navigate to [http://127.0.0.1:3000/](http://127.0.0.1:3000/)
to see the example in action.
