Configuration:
edit stream.js and set your twitter username password to see twitter's stream.

    var username = 'twitter_username', //ie: 'chovy'
        password = 'twitter_password'; //ie: 'xxxxx'

Go to last line and change your IP number to whatever IP you are serving from and port number if different than 8080, or you can use 'localhost' to test locally.

}).listen(8080, "192.168.1.1");

You may need to install some missing modules with npm. http://npmjs.org/

Once npm is installed, you can install the missing modules with:
$ npm install <module-name>
$ npm install json-line-protocol

Startup:
$ node stream.js
