##before publishing new version

- change repository to softwareone npm set registry https://npmregistry.pyracloud.com:4873/
- npm adduser
- make commit to repository
- run : npm version [patch|minor|major]
- it creates appropriate tag on git
- run npm publish
- git push --tags

```bash
npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]

npm [-v | --version]' to print npm version
npm view <pkg> version' to view a package's published version
npm ls' to inspect current package/dependency versions
```


