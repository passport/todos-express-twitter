This example illustrates how to use [Express](https://expressjs.com) 4.x and
[Passport](https://www.passportjs.org) to sign users in with [Twitter](https://twitter.com).
Use this example as a starting point for your own web applications.

## Quick Start

To get started with this example, clone the repository and install the
dependencies.

```bash
$ git clone git@github.com:passport/express-4.x-twitter-example.git
$ cd express-4.x-twitter-example
$ npm install
```

Once credentials have been obtained, create a `.env` file and add the following
environment variables:

```
TWITTER_CONSUMER_KEY={{INSERT_API_KEY_HERE}}
TWITTER_CONSUMER_SECRET={{INSERT_API_SECRET_KEY_HERE}}
```

Start the server.

```bash
$ npm start
```

Navigate to [`http://localhost:3000`](http://localhost:3000).


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
