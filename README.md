Converting a callback to a promise
To convert a callback to a promise, the first step is to create a new promise object. 
The promise constructor takes two arguments: a function to which two parameters, resolve and reject, are passed.

When an asynchronous operation succeeds, the resolve function is called, and when the operation fails, the reject function is called. 
The callback is invoked within this function, and the result is passed to the resolve or reject function, depending on the outcome of the operation. 
The promise object is returned after the callback has been activated so that it can be used in subsequent processing.

By converting callbacks to promises, developers are able to write code that is more concise and easier to understand.
