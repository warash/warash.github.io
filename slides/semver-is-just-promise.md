##semver is just a promise

how we can protect that on other machine after npm install everything will be working?

- npm install readable-stream --save --save-exact
- npm shrinkwrap
- npm install jquery --save --save-bundle - inside package
- configuration .npmrc
    - save=true
    - save-exact=true


```bash
npm config set save=true
npm config set save-exact=true
```
