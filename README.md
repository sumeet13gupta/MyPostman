
# MyPostman

myPostman is a web application similar to the postman app for testing REST apis dealing with GET, POST ,etc..

## Installation

Install node_modules using npm init and then run the ```requirements.sh``` to install al the required node packages we will be using .

To start the application on local server run ```MyPostman.sh```


________________________________________________________________________________

## Getting started
Make changes in your package.json file for the start script, we are using snowpack for this.
```
  "scripts": {
    "start": "snowpack dev"
  },
```
dependencies should look like :
```
  "dependencies": {
    "@codemirror/basic-setup": "github:codemirror/basic-setup",
    "@codemirror/commands": "github:codemirror/commands",
    "@codemirror/lang-json": "github:codemirror/lang-json",
    "@codemirror/view": "github:codemirror/view",
    "@popperjs/core": "^2.9.2",
    "axios": "^0.21.1",
    "bootstrap": "^5.0.2",
    "pretty-bytes": "^5.6.0"
  },
```
```
  "devDependencies": {
    "snowpack": "^3.6.0"
  }
```
________________________________________________________________________________
## Contributing

---
