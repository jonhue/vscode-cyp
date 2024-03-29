# vscode-cyp

VS Code syntax highlighting for [cyp](https://github.com/lukasstevens/cyp).

[Install with VS Code](https://marketplace.visualstudio.com/items?itemName=jonhue.vscode-cyp), [Install with Open VSX](https://open-vsx.org/extension/jonhue/vscode-cyp)

![image](https://user-images.githubusercontent.com/13420273/114928233-a80e6080-9e32-11eb-8280-549c54377d3e.png)

## Development

1. Install dependencies with `yarn install`
1. Run `yarn vsce package`
1. Using the command palette run the action `Install from VSIX...` and select the file that was generated when building the package

## Release

1. Change the version in `package.json`.
1. Create a pull request to merge the changes into `main`.
1. After the pull request was merged, create a new release listing the commits on `main` since the last release.
1. The release workflow will publish the package.
