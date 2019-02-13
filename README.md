# Wollok-TS [![Build Status](https://travis-ci.com/uqbar-project/wollok-ts.svg?branch=master)](https://travis-ci.com/uqbar-project/wollok-ts)

TypeScript based Wollok language implementation

## Usage 
[[TODO]]
- modules description
- examples


## Contributing

All contributions are welcome! Feel free to report issues on [the project's issue tracker](https://github.com/uqbar-project/wollok-ts/issues), or fork the project and [create a *Pull Request*](https://help.github.com/articles/creating-a-pull-request-from-a-fork/). If you've never collaborated with an open source project before, you might want to read [this guide](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/).

If you plan to contribute with code, here are some hints to help you start:


### Working Environment

Before anything else, you will need a *TypeScript* editor. We recomend [Visual Studio Code](https://code.visualstudio.com/) along with the following plugins:

- [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
- [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
- [Move TS](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

You might also want to copy the following configurations to your user settings (`ctrl+,`):

```json
  "window.menuBarVisibility": "default",
  "workbench.startupEditor": "none",
  "explorer.openEditors.visible": 0,
  "files.exclude": {
    "dist": true,
    ".vscode": true,
    "node_modules": true,
  },
  "git.enabled": false,
  "editor.tabSize": 2,
  "explorer.autoReveal": true,
  "editor.formatOnSave": true,
  "tslint.autoFixOnSave": true,
  "tslint.alwaysShowStatus": true,
  "workbench.statusBar.feedback.visible": false,
  "window.zoomLevel": 0,
  "workbench.colorTheme": "Visual Studio Dark",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.foldingStrategy": "indentation",
```

### NPM

You will also need to install [NPM](https://www.npmjs.com/). If you are not familiar with *dependency manager tools*, you can think of this program as the entry point for all the important tasks development-related tasks, like installing dependencies and running tests. After installing the client, go to the project root folder and run:

```bash
# This will install all the project dependencies. Give it some time.
npm install
```

After that, you are ready to start working. You can **run the tests and style checks** by typing:

```bash
# This will run tests for all the modules. Try to do this often and avoid commiting changes if any test fails.
npm test
```

A full list of the available scripts is listed on the `package.json` file, on the root folder.

### File Description
[[TODO]]: Describe what is each file

### Dependencies
[[TODO]]: Describe what we are usinng, give links, and explain what docs to read based on what you will be touching.
