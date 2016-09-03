###javascript package

- npm init / npm init --yes
- main property refers to entry point for our package
- if you are in git repo npm will add this to your package.json
- npm init can be re-run
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


