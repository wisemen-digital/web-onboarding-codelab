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
It provides code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, CSS, HTML and more.

[Download WebStorm](https://www.jetbrains.com/webstorm/download)

### Node.js
Node.js is an open-source, cross-platform, back-end JavaScript runtime environment 
that runs on the V8 engine and executes JavaScript code outside a web browser.

[Download Node.js](https://nodejs.org/en/download/)

### NPM vs PNPM

* [NPM](https://www.npmjs.com/get-npm)
NPM is the default package manager for the JavaScript runtime environment Node.js. The NPM program is installed on Node.js when you install it from its website.

* [PNPM](https://pnpm.io/installation)
PNPM is a fast, disk space efficient package manager. It is designed to be installed globally, and it installs all the packages that you need in your project in a single place, using symlinks.

  
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

## PROJECT: Overview

Now that we have a basic understanding of the project structure
and the different kinds of elements that a frontend should contain,
let's get started with building the acutal application.

Before we can create, update and delete todo's, we need to be able to login to the application.
There are several components that we need to create before we can start with the authentication flow.

We will need to create a view that contains a login form. This form will be used to send the login credentials to the backend. 
We will also need to create a service that will be used to send the login request to the backend.
Lastly, we will need to create a store that will be used to store the user information.
After we have created these components, we can start with the authentication flow.

Once the user is logged in, we will need to create a view that contains a list of todo's. 
This list will be fetched from the backend and displayed in a list view.
We will also need to create a service that will be used to fetch the todo's from the backend and a store that will be used to store the todo's.

After we have created these components, we can start with creating todo's. 
We will need to create a view that contains a form that can be used to create a new todo.
We will also need to create a service that will be used to send the todo to the backend.

## PROJECT: Http client

The most important aspect of programming is **separation of concerns.** and **DRY** (Don't Repeat Yourself).
This means that you should separate your code into different layers and files.
This will make your code more readable, reusable and easier to maintain.

You can easily do your calls in the component itself, but this will make your component less readable and harder to maintain in the future.

That's why we will start with creating a service that will be used to send the login request to the backend.

### Creating the HTTP client

- Add the `axios` package to the project.
- Create a new file called `httpClient.ts` in the `src/http` folder.
- Create a new instance of axios and export it.
- Add an interceptor that will be used to add the `Authorization` header to all requests.

### Creating the auth service
- Create a new file called `auth.service.ts` in the `src/services` folder.
- Import the `httpClient` from the `src/http` folder.
- Create a new function called `login` that takes a `username` and `password` as parameters.
- Use the `httpClient` to make a `POST` request to the `/login` endpoint.

## PROJECT: Router

The router is the core of Vue.js applications. It is used to navigate between different views.
It is also used to add guards to specific routes. This is useful when you want to protect a route from being accessed by unauthorized users.

### Creating the router

- Create a new file `router.ts` in the `src/router` folder.
- Implement a router using the `createRouter` function from `vue-router`.
- Create empty components called `LoginView.vue` and `TodoView.vue` in the `src/views` folder.
- Add a `login` and `todos` route to the router that lazy loads the `LoginView` and `TodoView` components.

### Router guards

- Add a `beforeEnter` guard to the `todos` route that checks if the user is logged in.
- If the user is not logged in, redirect the user to the `login` route.
- If the user is logged in, continue to the `todos` route.

## PROJECT: Auth store

### Creating the auth store

The store will help us to save the tokens after a successful login. 
Another reason to use a store is to manage your loading state.
This will help us to show a loading indicator when the user is logging in.
That's why we will always use a store to do our backend calls and never directly use the service in the component. (separation of concerns)

- Create a new file called `auth.store.ts` in the `src/stores` folder.
- Import the `auth.service` from the `src/services` folder.
- Create a new store using the `defineStore` function from `pinia`.
- Add a `accessToken` and `refreshToken` property to the store.
- Add a `login` function to the store that takes a `username` and `password` as parameters.
- Use the `auth.service` to make a `POST` request to the `/login` endpoint.
- Save the `accessToken` and `refreshToken` in the store after a successful login.
- PRO TIP: You can use the `useLocalStore` composable from VueUse to store the user information in the local storage.

## PROJECT: Login view

Now that we have created the store, service and router, we can start with creating the login view.
Views are the "Smart components" in our application. They are allowed to import stores, routers, dumb components, etc.

Our Login view will orchestrate the login flow. It will use the `authStore` to login the user and the `router` to navigate to the `TodoView` after a successful login.

### Creating your Login view

- Create a view called `Login.vue` in the `src/views` folder.
- Create a new file called `LoginForm.vue` in the `src/components` folder.
- Add a form that allows the user to enter a `username` and `password`.
- Add the `LoginForm` component to the `Login.vue` view.

### Creating the login flow

- Import the `useAuthStore` and `useRouter` in your `LoginView`.
- Create a new `authStore` and `router` instance.
- Add a `login` function that passes the credentials from the form to the `authStore`.
- Use the `router` to navigate to the `TodoView.vue` view after successfully logging in.

## PROJECT: Displaying todo's

Now that we have created the login flow, we can start with creating the todo view. 
After completing the login functionality, you should now have a good understanding of how we're going to create the todo view.

- Create a `todo.service.ts` in the `src/services` folder and implement the following functions:
  - The `getAll` function should return a list of todos.
  - Don't forget to type the response.
- Create a `todo.store.ts` in the `src/stores` folder and implement the `fetchAll` function.
- Create a `TodoList.vue` in the `src/components` folder and add it to the `TodoView.vue` view.
  - Display a list of todos.
  - Display a message when there are no todos
  - Display a loading state when the todos are being fetched.

## PROJECT: Creating Todo's

Now that we have created the todo view and have a list of our existing todo's, we can start with creating new todo's.

The creation of a todo will be done in a modal. This modal will be displayed when the user clicks on the `Create todo` button.
Modals are allowed to be smart components. The modal will contain a form that allows to enter the required information for creating a new todo. 

- Create a `TodoModal.vue` in the `src/components` folder and add it to the `TodoView.vue` view.
- Create a `TodoForm` component add it to the `TodoModal`.
  - The user can create a new todo by providing a `title`, `description` and `deadline`.
- Add validation to the form.
- Add a `create` function to the `TodoService` that takes a `TodoForm` as parameter. 
- Add a `create` function to the `TodoStore` that takes a `TodoForm` as parameter and calls the `create` function from the `TodoService`. 
- Handle the click of the submit button of the form in the `TodoModal` component and call the `create` function from the `TodoStore`.

## PROJECT: Updating todo's

The last step is to allow the user to update todo's. This will be done by clicking on the edit button of a todo.
We are going to extend the functionality of the `TodoModal` component to allow the user to update a todo.
To achieve this, we need to know if the modal is opened in `create` or `update` mode. The easiest way to do this is to check if a todo is passed to the modal.

- Add a parameters to the `open` function of the `TodoModal` component.
- If a todo is passed to the modal, we are in `update` mode. If no todo is passed, we are in `create` mode.
- Add a `update` and `delete` function to the `TodoService` that takes a `TodoForm` as parameter.
- Implement the `update` and `delete` function in the `TodoStore`.
- Handle the click of the **submit** and **delete** button of the form in and call the correct function from the `TodoStore`.

## Finishing up

Congratulations! You have successfully completed the Vue.js workshop. 
Make sure that your project has been pushed to your repository and that you have created a pull request. 
Fix any remarks that you have received from your mentor and wait for the final feedback.
