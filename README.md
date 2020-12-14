<h1 align="center">
ProgTrack
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>

ProgTrack is an online web app that allows teachers and students to keep track of student's grades. Built with MERN Stack

- Admin Dashboard
- Dark Theme UI

> MERN is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

MERN stack is the idea of using Javascript/Node for fullstack web development.

# Features!

- Add / Update / Delete User
- Add / Update / Delete Lesson
- Add / Update / Delete Grades

### Tech

- [MongoDB](https://www.mongodb.com/) - A document-oriented, No-SQL database used to store the application data.
- [ExpressJS](https://expressjs.com/) - fast node.js network app framework.
- [ReactJS](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [Redux](https://redux.js.org/) - A predictable state container for JavaScript apps.
- [nodeJS](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine

### Installation

Requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies

```sh
$ git clone https://github.com/georgesimos/el-tutor.git
$ npm install
$ npm run install-client // Installing react app dependencies
```

Start the server.

```sh
$ npm install
$ npm start or npm run dev // Starting the server
```

Start the client.

```sh
$ cd client
$ npm install
$ npm start
```
### or

Start server and client without to change folders. 

```sh
$ npm start or npm run dev // Starting the server
$ npm run start-client
```

### Database seeding
Database seeding is the initial seeding of a database with data.

```sh
$ node seed.js
```
> seed.js will auto generate some dummy users, lessons and grades. For Users creation faker npm package have been used!