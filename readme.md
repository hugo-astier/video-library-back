Directly taken from [Mosh Hamedani's repo Vidly-api-node](https://github.com/mosh-hamedani/vidly-api-node)

## Setup

You need to start this server to provide the back-end for
[video-library-front](https://github.com/hugo-astier/video-library-front).

### Install MongoDB

To run this project, you need to install the latest version of MongoDB Community Edition first.

https://docs.mongodb.com/manual/installation/

Once you install MongoDB, make sure it's running.

### Install the Dependencies

Next, from the project folder, install the dependencies:

    npm i

### Populate the Database

    node seed.js

### Start the Server

    npm start

This will launch the Node server on port 3900. If that port is busy, you can set a different point in config/default.json.

Open up your browser and head over to:

http://localhost:3900/api/genres

You should see the list of genres. That confirms that you have set up everything successfully.
