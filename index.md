author: JJ & KK
summary: Frontend onboarding
id: index
tags: Frontend, Vue
categories:
environments: Vue
status: Draft
feedback link: https://github.com/SolaceDev/solace-dev-codelabs/blob/master/markdown/android-test

# Wiselab Onboarding Frontend

## What you'll learn: overview

Welcome to the frontend onboarding! In this onboarding you will learn how development happens at Wisemen.
You will learn how to work with Vue, Vite, Tailwind, Figma, BitBucket and Jira.

## What you need: Prerequisites

### IDE

There are 2 different IDE's you can use to work with Vue. You can use either **Visual Studio Code** or **WebStorm**.

#### WebStorm

WebStorm is a JavaScript IDE with complete set of tools for client-side and server-side development and testing.
It provides code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript,
CSS, HTML and more.

[Download WebStorm](https://www.jetbrains.com/webstorm/download)

### Node.js

Node.js is an open-source, cross-platform, back-end JavaScript runtime environment
that runs on the V8 engine and executes JavaScript code outside a web browser.

[Download Node.js](https://nodejs.org/en/download/)

### NPM vs PNPM

* [NPM](https://www.npmjs.com/get-npm)
  NPM is the default package manager for the JavaScript runtime environment Node.js. The NPM program is installed on
  Node.js when you install it from its website.

* [PNPM](https://pnpm.io/installation)
  PNPM is a fast, disk space efficient package manager. It is designed to be installed globally, and it installs all the
  packages that you need in your project in a single place, using symlinks.

### Figma

Our designers work with **Figma**. You can view all of our designs here:

[Wisemen Figma](https://www.figma.com/files/team/1070403287155222588/Wisemen?fuid=1070747045190465434)

To access the designs you need to log in with your Wisemen account:
[Todo wireframes](https://www.figma.com/file/hebgv4Qx8VanMAQkO1NFpa/Onboarding-to-do?node-id=407-4095&t=2qdyy89lKwN7dFw3-0)

### BitBucket repository

Bitbucket is a web-based version control repository hosting service owned by Atlassian, for source code and development
projects that use the Git revision control system.

[Wisemen BitBucket](https://bitbucket.org/product)

### Jira access

For this onboarding you will be working with Jira to track your progress. You can find the Jira board here:
[Jira Todo]()

The Jira contains all the requirements for creating the to-do app.

*ToDo: Add link to Jira*

## What you'll do

### Project explanation

You will be creating a simple to-do app. The app can be used to create, edit and delete to-do's.
The backend is already created and you can find the documentation here:

[Backend documentation](https://bitbucket.org/wisemen/wisemen-onboarding-backend/src/master/)

### Requirements

- Login with your Wisemen gmail account
- View your to-do's in a list
- Create a new to-do
- Edit a to-do
- Delete a to-do
- Mark a to-do as done

### Designs

Insert designs here

## Project setup

<img width="300" src="img/projectSetup/cat_i_am_ready.gif">

### 1. Generate a new Vue3 project

> We use the latest version of Vue3 for this project. Vue3 is the latest version of Vue and has some new features and
> improvements over Vue2. You can read more about Vue3 here: [Vue3 website]('https://v3.vuejs.org/')
> Make sure you use the CLI version to create the project.

---

<img width="120" src="img/projectSetup/vite_logo.png">


### 2. Vite

Vite is a new breed of frontend build tool that significantly improves the frontend development experience. It consists
of two major parts:

- A dev server that provides rich feature enhancements over native ES modules, for example extremely fast Hot Module
  Replacement (HMR) that updates your changes in the browser in as little as 16 milliseconds.
- A build command that bundles your code with Rollup, pre-configured to output highly optimized static assets for
  production.

#### 2.1 Config

> Vite is configured using a `vite.config.js` file in the root of your project. This file is written in CommonJS format
> and should export a plain JavaScript object.


#### 2.2 Plugins

> Vite supports a plugin system that allows you to customize the behavior of Vite itself and integrate with other tools.
> Plugins can be configured in the `vite.config.js` file.

<img width="120" src="img/projectSetup/pnpm_logo.svg">
<img width="80" src="img/projectSetup/vs_icon.png">
<img width="140" src="img/projectSetup/npm_logo.png">

### 3. Package.json

> The package.json file is used to give information to npm that allows it to identify the project as well as handle the
> project's dependencies. npm can install the packages you specify in your package.json file.
> The main use of the package.json file is to list the packages that your project depends on and to ensure that your 
> colleagues get the same packages when they do `npm install`.

#### 3.1 Scripts

> The scripts property is used to specify a list of scripts that can be run using `npm run <script-name>`.
> It's written as a JSON object where each key is the name of a script and the value is the command to run for.
> Most common scripts are `start` and `build`.

#### 3.2 Dependencies vs Dev Dependencies

> Dev dependencies are dependencies that are only used during development and are not required for production.
> Dependencies are required for production.

<img width="120" src="img/projectSetup/tailwind_logo.png">


### 4. Tailwind CSS

> Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces. It's completely
> customizable, completely extensible, and amazingly feature-rich.

#### 4.1 Tailwind config

> Tailwinds config file is used to configure the framework. You can add custom colors, fonts, breakpoints and more.
> This is where you can customize the framework to your needs.

👉 [Tailwind website](https://tailwindcss.com/)

<img width="120" src="img/projectSetup/ESLint_logo.png">

### 5. ESLint config

> ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of
> making code more consistent and avoiding bugs. Is helps a lot with code formatting and makes it easier to write code.
> Also in team projects it helps to keep the code consistent.

👉 __Please make sure you use the Wisemen ESLint config file, read more here: [The Frontend bible ESLint config](https://thefrontendbible.com/eslint-config)__

<img width="120" src="img/projectSetup/vue_i18n_logo.svg">

### 6. i18n

> i18n is a short name for internationalization. It is a process of designing and developing a software application so
> that it can be adapted to various languages and regions without engineering changes.
> Within the company we use [Vue i18n](https://vue-i18n.intlify.dev/) to translate our applications.
> It's important to understand the power of this tool since it will save you a lot of time when creating multilingual
> applications.

<img width="120" src="img/projectSetup/typescript_logo.png">

### 7. What the Typescript


> TypeScript is a tool that helps developers write code with fewer bugs. TypeScript is a superset of JavaScript,
> meaning any valid JavaScript code is also valid TypeScript code. It helps a lot with type checking and makes it easier
> to write code.

<img width="220" src="img/projectSetup/google_fonts_logo.png">

### 8. ⚠️ Google fonts ⚠️
> It's important to know that we cannot use Google fonts CDN in our projects. This rule is only for public websites of our clients.
> We have alternative ways of using Google fonts in our projects. 

> 👉 __Please read more here: [Afstappen van Google Fonts en CDN javascript](https://appwise.atlassian.net/wiki/spaces/FRONT/pages/631734284/Afstappen+van+Google+Fonts+en+CDN+javascript).
> If you have any questions about this, please contact your team lead.__


### 9. @ Alias for src folder
> In our vue imports, we can use the @ alias to import files from the src folder. This is a lot easier than using relative paths.
> For example: 
```js 
import { Button } from '@/components
``` 
> instead of: 
```js
import { Button } from '../../components'
```
> This alias is configured in the `vite.config.js` file.
> Maybe do a little research about how you can configure your vite environment to accept the usage of this alias.

### 10. Important files

#### 10.1 .env

> The `.env` file is used to store environment variables. These variables can be used in your application.
> It is mainly used to separate development and production variables. For example, you can use a different API url in
> development than in production.

`⚠️ Using an .env is not required for this project.`

#### 10.2 .gitignore

> The `.gitignore` file is used to tell git which files it should ignore. For example, you don't want to commit your
> node_modules folder to git. This file is used to tell git to ignore this folder.

### That's it for now! 🎉 Soak it all in and let's get started with the project setup! 🚀

<img width="400" src="img/projectSetup/look_up.gif">




## Project Structure

<img width="300" src="img/projectStructure/organized.gif">

### Folder structure

For this project we will be using a 'split-by-type' folder structure. This is recommended for small applications.

You can read more about it here: [Folder structure](https://thefrontendbible.com/project-structure)

### Components

Components are the building blocks of Vue.js applications.
They are self-contained pieces of code that can be reused throughout your application.

You can read more about it here: [Components](https://thefrontendbible.com/components)

### Views

Views are the pages of your application. They are the components that are rendered when a specific route is visited.

You can read more about it here: [Views](https://v3.vuejs.org/guide/routing.html#basic-routes)

### Router

The router is the core of Vue.js applications. It is used to navigate between different views.

You can read more about it here:

- [Best practices](https://thefrontendbible.com/reusable-code/router)
- [Router](https://v3.vuejs.org/guide/routing.html#basic-routes)

### Stores

Stores are used to store the state of your application. This is useful when you want to share data between different
components.

You can read more about it here:

- [Best practices](https://thefrontendbible.com/reusable-code/stores)
- [Pinia](https://pinia.esm.dev/)

### Services & Http

Services are used to fetch data from the backend. These backend calls are made using the Http client.

You can read more about it here:

- [Best practices](https://thefrontendbible.com/reusable-code/services)

### Composables & Utils

#### Utils

Utils are reusable pieces of code that can be throughout your application.
They contain no state and are not tied to a specific component.

You can read more about it here: [Utils](https://thefrontendbible.com/reusable-code/utils)

#### Composables

Composables look like a util function, but the main difference is that they can contain state and leverage the
reactivity of Vue.js.

You can read more about it here: [Composables](https://thefrontendbible.com/reusable-code/composables)

### Assets

Assets are files that are used throughout your application. This can be images, fonts, icons, etc.

You can read more about it here: [Assets](https://thefrontendbible.com/assets)

### Locales

Locales are used to store the translations of your application. This is useful when you want to support multiple
languages.

You can read more about it here: [Locales](https://thefrontendbible.com/locales)

### Types & Interfaces

At Wisemen we use Typescript to type all of our code.
This is useful when you want to make sure that your code is correct and leverage the power of intellisense.
It will also help you to avoid bugs, improve your code quality and make your code more readable.

Lastly, your team will be able to understand your code better and don't have to make assumptions about the code.

You can read more about it here: [Types & Interfaces](https://thefrontendbible.com/types)

## Let's get started

Now that we have a basic understanding of the project structure
and the different kinds of elements that a application contains,
let's get started with building the application.

### 1. Creating your Login view

- Create a view called `Login.vue` in the `src/views` folder.
- Create a new file `router.ts` in the `src/router` folder.
- Implement a router using the `createRouter` function from `vue-router`.
- Add the `Login.vue` view to the router (lazy loaded).

### 2. Creating the HTTP client

- Create a new file called `httpClient.ts` in the `src/http` folder.
- Add the `axios` package to the project.
- Create a new instance of axios and export it.

### 3. Creating the auth service

- Create a new file called `auth.service.ts` in the `src/services` folder.
- Import the `httpClient` from the `src/http` folder.
- Create a new function called `login` that takes a `username` and `password` as parameters.
- Use the `httpClient` to make a `POST` request to the `/login` endpoint.

### 4. Creating the login form

- Create a new file called `LoginForm.vue` in the `src/components` folder.
- Add a that allows the user to enter a `username` and `password`.
- Add the `LoginForm` component to the `Login.vue` view.

### 5. Creating the Todo view

- Create a `TodoView.vue` in the `src/views` folder and add it to the router.
    - Make sure that the view is lazy loaded.
    - Make sure that the view is only accessible when the user is logged in.
- Create a `TodoList.vue` in the `src/components` folder and add it to the `TodoView.vue` view.
    - Display a list of todos.
    - Display a message when there are no todos
    - Display a loading state when the todos are being fetched.
- Create a `TodoForm.vue` in the `src/components` folder and add it to the `TodoView.vue` view.
    - The user can create a new todo by providing a `title` and `description`.
    - The user can update existing todos by selecting a todo from the list.

### 6. Creating the Todo service

- Create a `todo.service.ts` in the `src/services` folder and implement the following functions:
    - The `getAll` function should return a list of todos.
    - The `deleteById` function should delete a todo by id.
    - The `create` function should create a new todo.
    - The `update` function should update a todo.

### 7. Creating the Todo store

- Create a `todo.store.ts` in the `src/stores` folder and implement the `fetchAll` function.
    - The `fetchAll` function should call the `getAll` function from the `todo.service.ts` file.
    - Implement the `deleteById`, `create` and `update` functions.

## Documentation

- [The Frontend Bible](https://thefrontendbible.com/)
- [Vue.js](https://v3.vuejs.org/)
- [Vue Router](https://next.router.vuejs.org/)
- [Pinia](https://pinia.esm.dev/)
