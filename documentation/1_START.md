# React App process

This repository documents building a React App from scratch, starting with the `create-react-app` command. These Markdown files will document the process and any notes. The `git log` will also be a source of information for why things are changing at which point.

## Getting started

* Downloaded VSCode (never used it before)
    * Installed language extensions (HTML/CSS, ES7 + React)
    * Watched some [intro videos](https://code.visualstudio.com/docs/?dv=osx) to get familiar with using VSCode (in particular `git`)
* Ran `npx create-react-app job-tracker` in `~/Projects/`
* Git repository seems to already be initialised ~~and i'm not too sure why~~, looking at `$ git log` it seems the `create-react-app` command initialised the repo and made the first commit; `First commit` changes a line in the `index.html` file
* Committed `README.md` and add this document, pushed all to [GitHub](https://github.com/mdcass/job-tracker)

## VSCode customisation

### Run NPM scripts from the explorer

I wanted to run scripts from `package.json` within the IDE. [Tutorial here](http://www.matthiassommer.it/programming/testing/run-npm-scripts-in-visual-studio-code-with-a-click-of-a-button/). This added a `.vscode` settings directory to the project, which I added to `.gitignore` (right clicked on the file within the IDE and added it there).