[![npm version](https://img.shields.io/badge/vscode-install-blue.svg)](https://marketplace.visualstudio.com/items?itemName=sissel.scss-style-tag)

## SCSS Style Tag Support (VS Code)

Syntax highlighting and language and intellisense support for HTML style tags that use a `lang="scss"` or `lang="sass"` attribute.

## Example

```html

<style lang="scss">
  /* SCSS code here*/
</style>

<style lang="sass">
  /* SASS code here*/
</style>

```
#### SASS Languages Support
VS Code does not support pure SASS syntax, only SCSS syntax (currently). This is extension uses as [external extension](https://github.com/TheRealSyler/vscode-sass-indented) dependency which brings SASS language support to VS Code. If you have alternative extensions supporting SASS, consider uninstalling those to prevent grammar conflicts.
