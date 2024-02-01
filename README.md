# rtk-query-practice

### Prerequisite
- Clone this repository using the `git clone`
- Run `npm install` inside the root directory of the project
- Make a JSON server using json-server package and using the db.json file for it on port 3500
- run `npm start` in order to test the app

### **json-server**
Json server is basically takes your json file and create a crud api from it, in order to use it you will need to follow a few short steps:
- Run the command `npm install json-server -g` - this will install the package globally
- run the command ` json-server --watch data/db.json --port 3500` from the root directory - this will create the server for you on port 3500
- Have fun