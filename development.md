# Development
A good development process will introduce small, validated changes.

## Terminal
Terminal is an application that gives a user a command line for interacting with their operating system. The command line runs text commands.

### Installation
#### Mac
Look for the Terminal Application

#### Linux
Look for the Terminal Application

#### Windows
Use [GitBash](https://gitforwindows.org/). Command Line is a similar tool, but the specifics of working with it will look very different.

### Common Commands
```sh
ls # list all
pwd # list the current working directory
cd ~ # move to the root directory
cd ~/Documents # move to the documents folder
mkdir ~/dev # make a directory (folder) called dev in the root folder
```

### Git
Git is used to version control your code using a repository. A repository will allow changes to be composed into

#### .gitignore
The [.gitignore](./.gitignore) file contains that should not be added to the repository.

## Requirements
### Docker
Docker provides a declarative way of defining context.

#### Installation
To install, follow these [instructions](https://www.docker.com/get-started)

##### Verification
```
docker build -t latest .; docker run latest
```
This will output:
```
hello from Dockerfile
```
s
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

The testing is specified in [.github/workflows](./.github/workflows)
