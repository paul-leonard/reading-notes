# Paul's Reading Notes

## Code 201

### Class 13: Local Storage

**Reading Material for the Assignment**
1. Article
- [The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)



#### Article

##### [The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)
Cookies can only store 64KB of data and have to be sent/received with each webpage loading.  This can slow down your site.  Several third party and special use data stores were attempted over the years.  Thankfully, a companion spec to HTML introduced "HTML5 Storage".

The data is stored on a `localStorage` object that is part of the *global window object*.  This method is supported by most modern browsers and is based on *key/value pairs*.  Both the key and the value are stored as strings.  You can store other types of data (integers, floats, booleans) in the value, but will need to coerce the data to the appropriate data type using functions like `parseInt()` or `parseFloat()`.

`getItem()` and `setItem` are two main functions to use local storage.  `setItem` will silently overwrite the existing value if that key already exists.  `removeItem` deletes the key/value pair.  `key()` will help you identify all available keys.

The *storage* event can be watched to see when a local storage function is called.

The space allowed for localStorage is 5MB.

Two other methods for storing data local are in their younger stages.  They are Web SQL Database and IndexedDM (formerly known as WebSimpleDB).



[Return to Table of Contents for Paul's Reading Notes](https://paul-leonard.github.io/reading-notes/ "Go back to find more notes!")



---



Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").