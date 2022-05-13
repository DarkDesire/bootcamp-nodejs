# bootcamp-nodejs
Stub for creating simple nodejs project

## Created in VSCode
### Prerequisits:
1. Install chocolatey. 
2. Install nodejs: `choco install nodejs`

### Creating a new project
1. Creating folder.
2. Creating `package.json` file. 
```
{
    "name": "demo",
    "version": "1.0.0",
    "description": "",
    "main": "app.js",
    "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1",
      "start": "node app.js",
      "dev": "nodemon app.js"
    },
    "author": "",
    "license": "ISC",
    "dependencies": {
      "express": "^4.17.1",
      "nodemon": "^2.0.12"
    }
  }
```
3. Run `npm install`
4. Check result `npm run dev`
