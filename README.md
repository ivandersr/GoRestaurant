# GoRestaurant Web

This is an application to list the menu available from a restaurant, allowing <br/>
the user to manage the available options (remove/update) and to create new <br/>
dishes.

The dependencies are installed via Yarn package manager, and you can install and <br/>
run the application using the terminal commands listed next

### `yarn`
Run this command in your terminal to install all the dependencies locked in this <br/>
project.

### `yarn start`
This command will start application in a development environment. If this doesn't <br/>
trigger a new pop-up in your browser, access your [localhost](http://localhost:3000).

### `yarn json-server server.json -p 3333`
This starts the fake API used to run the application in development environment. <br/>If you have your own API, you can add its URL in the <br/>
in "src/services/api.ts".
