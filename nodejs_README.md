# npm commands

* npm init &nbsp;&nbsp;&nbsp;&nbsp;  --  to initialize a project. The parameters can be specified as asked by the prompt. This will create a **package.json** file containing information about the project.
* npm install --save-dev lite-server &nbsp;&nbsp;&nbsp;&nbsp;   -- to install a dependency which is exclusive to this project. **--save-dev** is used to mark it as a development only dependency, so this tool i.e., lite-server, will help us during development only.
     * In the **package.json** file, you can add below inside scripts json <br />
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     "start": "lite-server"
* npm start &nbsp;&nbsp;&nbsp;&nbsp;   --  npm start is a script command defined in a project's package.json file. It is typically used to start a Node.js application. When you run npm start, npm looks for a "start" script in the package.json file and executes the command associated with it.

![image](https://github.com/user-attachments/assets/b615a5d5-d5d5-4732-a5f8-eeb2409f19bf)

