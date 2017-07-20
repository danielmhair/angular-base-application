


Setting up computer for Programming Session 2
==============================================

Now that you have built components in HTML, CSS and Javascript, it is time to put them into Angular and convert your JavaScript into TypeScript. Its not that hard. So now its time to be introduced to `Typescript` and `Angular`.

## Overview:
Throughout this process, some of these words will not be familiar to you. Ignore that. Just know that they are needed to setup your computer to use `Typescript` and `Angular`. As we go through the session and in the future, these things will make more sense.

## Overview
- Install NodeJS
- Install Yarn
- Install Typescript
- Install Angular's CLI

### Step 1 - Install [NodeJS](https://nodejs.org/en/download/)
Click on the link "NodeJS" above. Select the operating system and then run the installer it downloads.

### Step 2 - Install [Yarn](https://yarnpkg.com/lang/en/docs/install/)
Make sure to install `Yarn` after you install `NodeJS` because `Yarn` uses `NodeJS` to install things. `Yarn` is a package manager. Click on the link and there is a button on the screen that says "Download Installer". Download it and install `Yarn` that way.

### Step 3 - Install Typescript
To install Typescript, you will use `Yarn`. This helps you install libraries into your application. Think of `Yarn` as a Home Depot for your app. You go to Home Depot to buy tools. Tools allow you to do more with your project. `Yarn` has hundreds of "tools" that you can use, which allow you to do more with your app.

In our case, we will use `Yarn` to install `Typescript`. Here is how you do it.

#### Step 3a - Open command line
To open the command line, either search for "Command Prompt" in Windows (or press CTRL+R => Type in "cmd.exe" => Press Enter). For MAC, search for "Terminal"

#### Step 3b - Install Typescript with Yarn
Run the following line in the command line / terminal.
```
yarn global add typescript
```

### Step 4 - Install Angular's CLI
The image below is from [Angular Cli's Guide](https://cli.angular.io).

These commands show them installing the cli through `npm`. It is just like `Yarn`. So those commands are a reference.

<img src="https://cli.angular.io/images/cli-logo.svg" />

This is to show you that any library installed with `npm` can be installed with `yarn`. The following commands below do the same thing as`npm`.
```
yarn global add @angular/cli
ng new my-dream-app
cd my-dream-app
ng serve -o
```
- `yarn global add @angular/cli` will install Angular's CLI for your computer. The `global` means to install this to your entire computer. Its just like installing a program with an `exe` file.
- `ng new my-dream-app` will create a new Angular application. `my-dream-app` can be anything. This is the folder that your app will be put into.
- `cd my-dream-app` will change directories (`cd`) to the folder `my-dream-app`.
- `ng serve` will compile your app, or rather start your app. The `-o` will automatically open the browser for you.
