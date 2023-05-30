author: JJ & KK & NB
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

This onboarding is designed to be completed in roughly 3-4 days. 
This does not mean you have to complete it in 3-4 days. People with more experience will be able to complete it faster than people with less experience.

You will be working on a small to-do app.
This app will be used to learn the same way we, as front-end developers work at Wisemen. You will be working with the tools we use at Wisemen and you will be working with the same workflow.

We also expect you to make pull request of your work so your buddy can review your code and keep track of your progress.
The way we do this will be explained in the onboarding.

Good luck on becoming the front-end developer you are meant to be!



![](img/programmer.gif)




## What you need: Prerequisites

### IDE

There are 2 different IDE's you can use to work with Vue. You can use either **Visual Studio Code** or **WebStorm**.

#### WebStorm
WebStorm is a JavaScript IDE with complete set of tools for client-side and server-side development and testing.
It provides code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, CSS, HTML and more.

Webstorm is a paid IDE. You can get a license from Wisemen. Ask your buddy!

[Download WebStorm](https://www.jetbrains.com/webstorm/download)


#### Visual Studio Code
Visual Studio Code is a source-code editor developed by Microsoft for Windows, Linux and macOS. 
It includes support for debugging, syntax highlighting, intelligent code completion, snippets, and code refactoring.

Visual Studio Code is a free IDE. You can download it from the website.

[Download vscode](https://code.visualstudio.com/download)

Choose the IDE you want to work with and download it.



### Node.js
Node.js is an open-source, cross-platform, back-end JavaScript runtime environment 
that runs on the V8 engine and executes JavaScript code outside a web browser.

Node.js is necessary to run the Vue project. You can download it from the website.

[Download Node.js](https://nodejs.org/en/download/)

### NPM vs PNPM

* [NPM](https://www.npmjs.com/get-npm)
NPM is the default package manager for the JavaScript runtime environment Node.js. The NPM program is installed on Node.js when you install it from its website.

* [PNPM](https://pnpm.io/installation)
PNPM is a fast, disk space efficient package manager. It is designed to be installed globally, and it installs all the packages that you need in your project in a single place, using symlinks.

The difference between NPM and PNPM is that PNPM uses symlinks to link packages to your project. This means that if you have multiple projects that use the same package, it will only be installed once on your computer. This saves a lot of disk space.
PNPM is also faster than NPM because it uses symlinks.

### Figma
Our designers work with **Figma**.
Figma is a vector graphics editor and prototyping tool which is browser-based or can be installed on macOS or Windows.
We recommend you to install the desktop app.

[Download Figma](https://www.figma.com/downloads/)

Take a look around in Figma and try to get familiar with the tool. You will be using it a lot in the future.
You can view all of our designs here:

[Wisemen Figma](https://www.figma.com/files/team/1070403287155222588/Wisemen?fuid=1070747045190465434)

To access the designs you need to log in with your Wisemen account:
[Todo wireframes](https://www.figma.com/file/hebgv4Qx8VanMAQkO1NFpa/Onboarding-to-do?node-id=407-4095&t=2qdyy89lKwN7dFw3-0)

### BitBucket repository
Bitbucket is a web-based version control repository hosting service owned by Atlassian, for source code and development
projects that use the Git revision control system.

All your future projects will be hosted on BitBucket.

[Wisemen BitBucket](https://bitbucket.org/product)

If you are not yet familiar with Bitbucket and/or Git, Here is great article to get you started:
[Bitbucket Git tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control)

We also expect you to make pull request of your work so your buddy can review your code and keep track of your progress.
In the article above you can find a section about pull requests to get you started!

### Jira access

For this onboarding you will be working with Jira to track your progress. You can find the Jira board here:
[Jira Todo]()

Jira is used to track the progress of your project and manage the tasks that need to be done.
All the requirements for the to-do app are in the Jira. You will be creating tasks in the Jira to keep track of your progress. (weet niet of ze zelf ticketjes hiervoor moeten maken of we ze dat geven?)

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

### 1. Generate a new Vue3 project

```typescript
TODO
```

### 2. Vite

Vite is a new breed of frontend build tool that significantly improves the frontend development experience. It consists of two major parts:

- A dev server that provides rich feature enhancements over native ES modules, for example extremely fast Hot Module Replacement (HMR) that updates your changes in the browser in as little as 16 milliseconds.
- A build command that bundles your code with Rollup, pre-configured to output highly optimized static assets for production.

#### Config

> Vite is configured using a `vite.config.js` file in the root of your project. This file is written in CommonJS format and should export a plain JavaScript object.

```typescript
TODO
```

#### Plugins

> Vite supports a plugin system that allows you to customize the behavior of Vite itself and integrate with other tools. Plugins can be configured in the `vite.config.js` file.

```typescript
TODO
```

### 2. Package.json

> The package.json file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies. npm can install the packages you specify in your package.json file.

#### Scripts

#### Dependencies vs Dev Dependencies

### 3. Tailwind CSS

> Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces. It's completely customizable, completely extensible, and amazingly feature-rich.

```typescript
TODO
```

### 4. ESLint config

> ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs. In many ways, it is similar to JSLint and JSHint with a few exceptions:
    
```typescript
TODO
```

### 5. i18n

> i18n is a short name for internationalization. It is a process of designing and developing a software application so that it can be adapted to various languages and regions without engineering changes.

```typescript
TODO
```

### 6. What the Typescript

> TypeScript is a typed superset of JavaScript that compiles to plain JavaScript. Any browser. Any host. Any OS. Open source.

```typescript
TODO
```

## Project Structure

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
Stores are used to store the state of your application. This is useful when you want to share data between different components.

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

Composables look like a util function, but the main difference is that they can contain state and leverage the reactivity of Vue.js.

You can read more about it here: [Composables](https://thefrontendbible.com/reusable-code/composables)

### Assets
Assets are files that are used throughout your application. This can be images, fonts, icons, etc.

You can read more about it here: [Assets](https://thefrontendbible.com/assets)

### Locales
Locales are used to store the translations of your application. This is useful when you want to support multiple languages.

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
