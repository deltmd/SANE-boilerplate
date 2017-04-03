# SANE-boilerplate
This is my SANE stack boilerplate connecting to a SQL database. It also has sweet alerts pre built into it.

Clone and init your repo. The starting point is index.js.
npm install
create a config.js file connecting to your database and setting your server port as below.

module.exports = {
    massive: "YourServerName://yourHost:YourPassword@yourHostLocation/yourDatabaseName",
    secret: "Your Connection String Secret For Variable Uses",
    port: 8001 or whatever you want it to be
    }

If this is set up correctly you should be able to run your server; I use nodemon. when rendered it should show everything in the test table of the database.
NOTE: landingCtrl.js and landingServ.js has the test path for the request to the database.
