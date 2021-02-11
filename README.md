![ScreenShot](https://github.com/dlynnea/SeH-todo-app/blob/main/public/preview.png)

# Create Reagent App

A simple way to bootstrap a ClojureScript (CLJS) web-app using:

- [Shadow-CLJS](http://shadow-cljs.org/) as the build tool / compiler

- [Reagent](https://github.com/reagent-project/reagent) (CLJS wrapper around [React](https://reactjs.org/)) for building your user interface

---

## Getting Started

### 1. Clone Repository

Start in your terminal by creating a folder (in your current working directory), change directory into that folder and clone the project:

```
mkdir project-folder
```

```
cd project-folder
```

```
git clone https://github.com/dlynnea/SeH-todo-app.git
```

### 2. Install dependencies

Note: This step creates a `node_modules` folder with all the dependencies in your project folder. You can use either `yarn` or `npm` as your package manager.

First cd into the project folder Seh-todo-app, then install

```
cd SeH-todo-app
```

```
npm install
```

Note: Creates a `package-lock.json` file in your project folder.

### 3. Run server

```
npm start
```

### 4. Open your browser

Then open http://localhost:3000/ in your browser to see the app.


> Note: This approach to scaffolding an app was heavily inspired by [create-react-app](https://create-react-app.dev/), a very popular way to get started with a ReactJS app in the JavaScript community.

> Note also: Unlike the setup created by _create-react-app_, your project is not automatically initialized as a Git repo. However, a `.gitignore` file is included. Please run `git init` to create a Git repo in your project folder.

---