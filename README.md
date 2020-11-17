# modern-javascript-project

## How to start a modern JavaScript project


* Create a new folder

    ```bash
    mkdir my-project
    ```

* Inside `my-project`, initialize the npm project on the command

    ```bash
    npm init
    ```

* Create a folder for your project's source code

    ```bash
    mkdir src
    ```

* Inside `src` create a new file to write your first JavaScript

    ```bash
    index.js
    ```

* Set the start command on scripts in package.json file

    ```bash
    "start": "node src/index.js",
    ```

* Finally, at the root of the project, run the script

    ```bash
    npm start
    ```