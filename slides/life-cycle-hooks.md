##package.json lifecycle hooks

- prepublish: Run BEFORE the package is published. (Also run on local npm install without any arguments.)
- publish, postpublish: Run AFTER the package is published.
- preinstall: Run BEFORE the package is installed
- install, postinstall: Run AFTER the package is installed.

example

```json
{
scripts:{
        prepublish: "gulp build",
        }
}
```
