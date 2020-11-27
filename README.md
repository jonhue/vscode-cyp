# vscode-cyp

VS Code syntax highlighting for [cyp](https://github.com/lukasstevens/cyp).

[**Install**](https://marketplace.visualstudio.com/items?itemName=jonhue.vscode-cyp)

## Development

1. Install dependencies with `yarn install`
1. Run `yarn vsce package`
1. Using the command palette run the action `Install from VSIX...` and select the file that was generated when building the package

## Release

1. Change the version in `package.json`.
1. Create a pull request to merge the changes into `master`.
1. After the pull request was merged, create a new release listing the commits on `master` since the last release.
1. The release workflow will publish the package.
