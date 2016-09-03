##javascript module

- built using CommonJS syntax

```javascript
var dependency = require('dependency-module');

module.exports = function (a,b) {
	return a + b;
};
```


- bigger modules grouped in folder and exposed via index.js


```javascript
// models/index.js
module.exports.user = require('./user')
module.exports.token = require('./token');
module.exports.role = require('./role');
require('./private')();

//some other js file
var models = require('./models')
models.user.name = "Janusz"
```
