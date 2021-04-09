# Spotify Authorization Code flow sample

> Adapted from the Spotify [web-app-auth-examples](https://github.com/spotify/web-api-auth-examples) repo.

This repository contains a basic application showing the Authorization Code OAuth 2.0 flow for [authenticating against the Spotify Web API](https://developer.spotify.com/documentation/general/guides/authorization-guide/#authorization-code-flow).

## Install Node.js and app dependencies

This example runs on Node.js. On the [Node.js website](http://www.nodejs.org/download/) you can find instructions on how to install it.

Once installed, clone the repository and install its dependencies by running:

    npm install

### Using your own credentials

You will need to register an app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to your [Spotify for Developers Dashboard](https://developer.spotify.com/dashboard) and create an application. For the example, I registered this Redirect URI:

* http://localhost:8888/callback

Once you have created your app, replace the `client_id`, `client_secret`, and `redirect_uri` in the example with the ones you get from My Applications.

## Running the example

In order to run the example, run its `app.js` file:

    cd authorization_code
    node app.js

Then, open http://localhost:8888 in a browser.
