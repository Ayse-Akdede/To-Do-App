# Todoapp

To Do App with Angular 9 and Firebase database.

Here is my [demo link](https://angular-firebase-todoapp.netlify.com/).

## Open a local server

- To open a local you need to go to your project's directory.
- Open a terminal and run `ng serve --open`
- Now you can navigate to `http://localhost:4200/`.

> The app will automatically reload if you change any of the source files.

## Update of the app

- First step is modify and update everything. (css / html / ts)
- Make sure to save all files.
- Delete the `/dist` file inside your directory.
- Go to the project's directory and open terminal.
- Run `ng build --prod` to build the project.
- After built is done you can `add` , `commit`and `push`.

> If there is an error when `ng build --prod` then you need to update everything.

## Update if error on 'serve' or 'build'

- Updating angular and the CLI using:

```sh
ng update @angular/cli @angular/core
```

- Install bootstrap again with npm

```sh
npm install bootstrap
```

- Install ng-bootstrap

```sh
npm install --save @ng-bootstrap/ng-bootstrap
```

- Install Localize

```sh
ng add @angular/localize
```
