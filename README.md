# oc-cm-common-styles

### To use oc-cm-common-styles
Common styles are in Sass format.
Import in Javascript:
```javascript
import '@opuscapita/oc-cm-common-styles';
```
Import in Sass
```javascript
@import '~@opuscapita/oc-cm-common-styles';
```

### Development workflow with `npm link`
##### Link local package to your project
* Run `npm link` at `oc-cm-common-styles` root to make your local package linkable
* Run `npm link @opuscapita/oc-cm-common-styles` at project's dir that's using `oc-cm-common-styles` to use local package
##### Development
* Develop the styles and check with project using the package
##### Unlink local package
* Run `npm unlink @opuscapita/oc-cm-common-styles` at project's dir that's using `oc-cm-common-styles`
* Run `npm install` to install remote copy of the `@opuscapita/oc-cm-common-styles` package

### Changelog
* Remember to update the CHANGELOG.md file with information about the changes to `src`

### Contributing
* Make a new branch for the changes
* Update `CHANGELOG.md` file
* Commit changes
* Push changes
* Make a pull request
* Merge the pull request and delete the development branch

### Creating a new version release
* Run `npm version [major|minor|patch]` [Info](https://docs.npmjs.com/cli/version)
