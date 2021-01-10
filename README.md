# 🙏🏽 deferred promise

Create deferred promise who can be resolve or reject from anywhere.

## Usage

````js

import deferredPromise from "@wbe/deferred-promise";
 
const deferred = deferredPromise();

deferred.promise.then(() => {
  // deferredPromise is resolved! 
});

// when needed, resolve this promise  
deferred.resolve();
// or reject it
deferred.reject();
````

## Credits

Willy Brauner

## Licence 

[MIT](LICENSE)



