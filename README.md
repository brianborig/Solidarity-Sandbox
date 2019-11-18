# Solidarity-Sandbox
Repo for Extensis solidarity demo

## What is Solidarity? Why would we use it?
* Solidarity is an environment checker for project dependencies.
* It can be useful when onboarding engineers onto a team. When running it, a developer can clearly see the requirements and install them even across different OS's.

## The Absolute Basics
### First Steps
This project already has solidarity set up but if you were hoping to set this up on one of your own projects:

1. Install -> `npm install solidarity` or `yarn add solidarity` in your project root.
2. Install a snapshot plugin shown [here](https://www.npmjs.com/package/solidarity) and take a snapshot with `solidarity snapshot` or [write a .solidarity file by hand](https://infinitered.github.io/solidarity/#/docs/options)
3. Run solidarity with `npm/yarn solidarity` (this project uses yarn)

### Navigating the solidarity file
#### Rules
There are 5 different types of rules:
1. CLI rules -> Will make sure the specified CLI is installed on the system
2. Environment rules -> Will look for the specified environment variable
3. File rules -> Will look for the specified file
4. Directory rules -> Will look for the specified directory
5. Shell rules -> Allows you to specify a shell command and match some expected output with the observed

### More info
More info is available in [infinitered's git](https://github.com/infinitered/solidarity/blob/master/docs/options.md#environment-rules) and [npm page](https://www.npmjs.com/package/solidarity).
