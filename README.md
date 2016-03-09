# Mochila Solidaria


Make sure you have installed all of the following prerequisites on your development machine:
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
  * Node v5 IS NOT SUPPORTED AT THIS TIME! 
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).
* Ruby - [Download & Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)
* Bower - You're going to use the [Bower Package Manager](http://bower.io/) to manage your front-end packages. Make sure you've installed Node.js and npm first, then install bower globally using npm:

```bash
$ npm install -g bower
```

```bash
$ npm install -g grunt-cli
```

```bash
$ gem install sass
```

```bash
$ npm install gulp -g
```


## Install Node.js dependencies.

```bash
$ npm install
```

## Running Your Application
After the install process is over, you'll be able to run your application using Gulp

```
$ gulp
```

Your application should run on port 3000 with the *development* environment configuration, so in your browser just go to [http://localhost:3000](http://localhost:3000)

## Running in Production mode
To run your application with *production* environment configuration, execute grunt as follows:

```bash
$ gulp prod
```

## Testing
You can run the full test suite included with MEAN.JS with the test task:

```bash
$ gulp test
```

This will run both the server-side tests (located in the app/tests/ directory) and the client-side tests (located in the public/modules/*/tests/).

To execute only the server tests, run the test:server task:

```bash
$ gulp test:server
```

And to run only the client tests, run the test:client task:

```bash
$ gulp test:client
```


