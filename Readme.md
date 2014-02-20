*This repository is a mirror of the [component](http://component.io) module [segmentio/memoize-async](http://github.com/segmentio/memoize-async). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-memoize-async`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# memoize-async

  Memoize the results of async functions

## Installation

    $ component install segmentio/memoize-async

## API

  ```javascript
  var memoize = require('..');

  User.get = memoize(User.get);

  User.get('a@a.com', function (err, user) {
    // do some stuff
  });

  // ... later we will immediately get the user

  User.get('a@a.com', function (err, user) {

  });


  ```



## License

  MIT
