#### Overview

> Simple node-red & express server

Node-red-express is a lightweight wrapper for node-red using express server.

- Moves the flows.json file to the project directory
- Merges node-red [settings file](<(https://nodered.org/docs/user-guide/runtime/settings-file)>) with index.js
- Includes rudimentary example flow to demonstrate how to use npm packages and environment variables within node-red.

---

#### Installation

Clone this repository to your local system and change into this directory

```

```

Install node modules

```
npm install
```

Start Node-RED

```
npm start
```

Once Node-RED is running you can access the editor from your browser

[http://localhost:8000/](http://localhost:8000/)

---

#### Docker

Use the following command for the simplest way to get started with this project. (Note - The prebuilt docker image from dockerhub exposes node-red on port 8000)

```
$ docker run -p 8000:8000 bimlauncher/node-red-express
```

_Or_ Build and tag your own image. From within the node-red directory, do:

```
$ docker build -t bimlauncher/node-red-express .
```

Then, open a browser to node-red:

```
$ localhost:8000
```

You can start and stop containers without losing the flows files. First, do `docker ps` to get list of running containers. Then do `docker stop <CONTAINER ID>` to stop the container. Alternatively, do `docker start <CONTAINER ID>` to start it up again.

#### Licence

MIT

---

#### Similar Node-red reference start projects

- https://github.com/dceejay/node-red-project-starter
- https://github.com/natcl/node-red-project-template
