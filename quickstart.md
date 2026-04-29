# Welcome to Rux VS Code Extension

## What's in the folder

- This folder contains all the files necessary for Rux extension.
- `package.json` - this is the manifest file in which you declare Rux language support and define the location of the grammar file that has been copied into Rux extension.
- `syntaxes/rux.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
- `language-configuration.json` - this is the language configuration, defining the tokens that are used for comments and brackets.

## Get up and running straight away

- Make sure the language configuration settings in `language-configuration.json` are accurate.
- Press `F5` to open a new window with Rux extension loaded.
- Create a new file with a file name suffix matching Rux language.
- Verify that syntax highlighting works and that the language configuration settings are working.

## Make changes

- You can relaunch the extension from the debug toolbar after making changes to the files listed above.
- You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with Rux extension to load changes.

## Add more language features

- To add features such as IntelliSense, hovers and validators check out the VS Code extenders documentation at https://code.visualstudio.com/api/language-extensions/overview

## Install extension

To start using Rux extension with Visual Studio Code install `@vscode/vsce` globally

```sh
npm install -g @vscode/vsce
```

Create `vsix` file from files and install extension in VS Code

```sh
vsce package
code --install-extension .\rux-lang-0.1.0.vsix
```
