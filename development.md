# Development
A good development process will introduce small, validated changes. This document shows how to do so

## Requirements

### Terminal
Terminal is a program for executing bash commands. This gives an environment for being able to manipulate our operating system through code.

#### MacOs
Terminal comes with git already included.

#### Windows
Use [Git Bash](https://gitforwindows.org/)

### Git
Git is used to version control your code using a repository. A repository will allow changes to be composed into

#### Installation
https://www.atlassian.com/git/tutorials/install-git

##### MacOs
Terminal comes with git already included, but you may need to install xcode with the following command:
```
xcode-select --install
```

##### Windows
Use [Git Bash](https://gitforwindows.org/)

#### Github
This repository is hosted on github.com. It can be found here: TODO

#### .gitignore
The [.gitignore](./.gitignore) file contains that should not be added to the repository.

### Docker
Docker provides a declarative way of defining context.

## Editors
Editors are used to edit code. Some come with advanced tooling to help edit more efficiently.

### Visual Studio Code
Visual Studio Code (VSCode) is a light-weight editor. It can be downloaded [here](./TODO).

VSCode has a [directory](./vscode) that allows for configuration. More information can be found in it's [README](./vscode/README.md).

### Vim
Vim is a purely text-based editor, that is, it does not allow for mouse interactions. To exit the editor, type `:wq`

### Repl.it
Repl.it is an online editor. It allows for a developer to interact with a repository without having to run it locally on a computer.

## Testing
Code is meant to do something, usually displaying information or manipulating information. As such, we can and should validate that the code works correctly. More importantly, we can validate the process. Functionality that isn't automatically will eventually stop existing, and this eventuality is often sooner than one thinks.

### Continuous Integration
Continuous Integration allows us to validate our code automatically. We can create rules for running and executing code. The integration describes a the process of integrating changes in our code into our code base. We want small, continuous, and validated changes being introduced into our codebase.

#### Github Actions


## Deployment

