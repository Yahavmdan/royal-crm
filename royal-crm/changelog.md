# add routing and create customers component

# create paragraphCapital pipe

- use the pipe on description in page-header.component.html

# set page-header component

- create page-header component
- replace page header in contacts.component to a page-header component

# refactor: contacts component

- create interface for contact objects
- create service for contacts
- set template to show contact's data from service

# set contacts component and show in app.component

# set sidenav component and show in app.component

# set footer component and show in app.component

# set navbar component and show in app.component

# set up main page layout

# install bootstrap and bootstrap icons

- `npm i bootstrap bootstrap-icons`
- set up bootstrap's scripts and styles in angular.json

  - add in build the following

    ```javascript
    "build": { "styles": [ "src/styles.scss", "node_modules/bootstrap/dist/css/bootstrap.css", "node_modules/bootstrap-icons/font/bootstrap-icons.css" ], "scripts": ["node_modules/bootstrap/dist/js/bootstrap.bundle.js"]
    ```

# initialize new angular project

- ng new royal-crm
- routing Y
- styling SCSS
