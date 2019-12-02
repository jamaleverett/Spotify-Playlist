Spotify Accounts Authentication Examples
This project contains basic demos showing the different OAuth 2.0 flows for authenticating against the Spotify Web API.

These examples cover:

Authorization Code flow
Client Credentials flow
Implicit Grant flow
Installation
These examples run on Node.js. On its website you can find instructions on how to install it. You can also follow this gist for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

$ npm install
Using your own credentials
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to your Spotify for Developers Dashboard and create your application. For the examples, we registered these Redirect URIs:

http://localhost:8888 (needed for the implicit grant flow)
http://localhost:8888/callback
Once you have created your app, replace the client_id, redirect_uri and client_secret in the examples with the ones you get from My Applications.

Running the examples
In order to run the different examples, open the folder with the name of the flow you want to try out, and run its app.js file. For instance, to run the Authorization Code example do:

$ cd authorization_code
$ node app.js
Then, open http://localhost:8888 in a browser.
