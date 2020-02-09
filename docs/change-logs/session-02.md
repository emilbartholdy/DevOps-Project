# Session 2

### Installation of runtime environment and application dependencies

1. Install *Node.js* runtime and *NPM* (package manager for the Node JavaScript platform) with the following commands:

   ```bash
   $ sudo apt-get install nodejs
   $ sudo apt-get install npm
   ```

2. Inside the application directory, run the following command to install all dependencies for the Node applications:

   ```bash
   $ npm i --save-dev
   ```

### Running E2E tests

Inside the application directory, execute the following command to run the E2E tests:

```bash
$ npm test
```
