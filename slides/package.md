###javascript package

- npm init
- main property refers to entry point for our package

```json
{
  "name": "demo",
  "version": "1.0.0",
  "description": "my demo project",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}

```

exaple usage:
```javascript
require('path\to\my\funky\module');
```

- looks for file module.js in funky folder
- looks for package.json in funky\module folder
- looks for index.js in funky\module folder


