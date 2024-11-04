# Required Tools

- [Required Tools](#required-tools)
  - [Integrated Development Environment](#integrated-development-environment)
  - [Node and NPM/FNM](#node-and-npmfnm)
    - [Checking Node.js and npm Installation](#checking-nodejs-and-npm-installation)
  - [Deno](#deno)
    - [Install Deno](#install-deno)
      - [MacOS/Linux](#macoslinux)
      - [Windows](#windows)
  - [Python](#python)


The following file contains **REQUIRED** tools you will need to install for this course. While not all of it required immediately, you will need most of them at some point throughout the semester. It is best to install all these the first week, and meet with the TAs and  Instructor if you are unable to get the tool setup. 

## Integrated Development Environment

We don't have a single required environment for this course, but you will probably want [VSCode](https://code.visualstudio.com/Download) or [WebStorm](https://www.jetbrains.com/webstorm/download/).

For VSCode you will find there are a number of useful extensions. Many of them you will already have. It is also worth noting that HTML/CSS/Typescript and Javascript come pre-supported with VS code.

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Mermaid Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
* [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## Node and NPM/FNM

Node.js and NPM are essential tools for modern web development. You can download and install them from the [official Node.js website](https://nodejs.org/). We recommend using the [package manager
options](https://nodejs.org/en/download/package-manager) for Windows `fnm` is popular and for linux/mac `npm` is popular. As of writing this information sheet, `vfox` is a relatively new manager that is cross-platform. It may also be a good one to look into. 

> [!WARNING]
> For both, you may need to open a new terminal window (outside of VS code) between the first step and next steps. 


### Checking Node.js and npm Installation

To verify if Node.js and npm are installed correctly on your computer, follow these steps:

1. Open your terminal.
2. Type `node -v` and press Enter. This command checks the version of Node.js installed. If Node.js is installed correctly, you will see a version number, such as `v22.11.0`.
3. Type `npm -v` and press Enter. This command checks the version of npm installed. If npm is installed correctly, you will see a version number, such as `10.9.0`.

If you see version numbers for both Node.js and npm, it means they are installed correctly. If not, you may need to install or troubleshoot the installation process.



## Deno

Deno is an open-source runtime for TypeScript and Javascript. We will be using it as means for free hosting in a number of our examples. With that said, you may also have other options for free hosting - which you will find will give you flexibility. 

### Install Deno

You should follow the [getting started guide](https://docs.deno.com/runtime/) in particular the [installation guide](https://docs.deno.com/runtime/getting_started/installation/).

For macOS and Linux, curl is the most popular option, though Homebrew is popular on macOS. Windows the `winget` option is the easiest. Examples below

#### MacOS/Linux
```terminal
curl -fsSL https://deno.land/install.sh | sh
```

#### Windows
```terminal
winget install DenoLand.Deno
```

For windows, macOS, and linux you can also use [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) which involves making sure rust is installed on your system. 


> [!WARNING]
> Deno has its own managed version of typescript it uses and many of our examples will include using deno to go from typescript to javascript. However, for some projects you may want to install typescript locally by using NPM.
> ```terminal
> npm install -g typescript
> ```

## Python
A number of our labs will require the use of python. Make sure you have [python installed](https://www.python.org/downloads/). 