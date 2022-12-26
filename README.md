AngularJS is a JavaScript web framework that is widely recognized for its simplicity and lightweight nature, making it an ideal choice for the development and design of web applications. With its intuitive and user-friendly features, AngularJS allows developers to quickly and efficiently build robust and visually appealing web apps.

To install AngularJS using npm, you can use the following command in your terminal or command prompt:

```sh
npm install angular
```
To run an AngularJS project, you can use the following command:

```sh
ng serve
```
This will start a development server that allows you to view and test your AngularJS app in a browser.

# Components
To create a new component in Angular, you can use the Angular CLI (Command Line Interface) to generate the component files. The Angular CLI is a command-line tool that allows you to easily create, build, and deploy Angular applications.

To create a new component using the Angular CLI, you can use the following command:

```sh
ng run c
```
It will ask name of components and This will create a new folder for your component in the components/directory, with the following files:
- `component-name.js`: This is the JavaScript file that defines the component class.
- `component-name.html`: This is the HTML template file for the component.
- `component-name.css`: This is the CSS file for the component.

You can then add your component's logic and styling to these files as needed.

# Routing/Navigate
In AngurJS, you can use the `go` directive to navigate between different components in your application. This directive is used in an HTML element, and it tells the router which component to display when the element is clicked.

To navigate to a component named userProfile, you can use the following HTML code:

```html
<button go="userProfile">Go to UserProfile</button>
```
This will create a button that, when clicked, will navigate the user to the userProfile component.

To use the `go` directive, you will need to set up routing in your AngurJS application. This involves defining routes for each component.

# Include/Load Components
In AngurJS, you can use the `template` directive to define a reusable template that can be inserted into the DOM at a later time. The `template` directive is similar to a <template> element in HTML, but it is only recognized by AngurJS.

You can then insert the header template into the DOM by using the `template` directive, like this:

```html
<div template="header"></div>
````

# Varibale Passing
  
To pass any value from one component to another component, you need to use setValue() and getValue() as functions.

For example, you want to pass "name" from the "UserForm" component to the "UserDetails" component.
So in the "UserForm" component:
```js
setValue("name", "Rohit Chouhan")
 ```

And in the "UserDetails" component:
```js
getValue("name")
```
