<h1 align="center">
ProgTrack
</h1>

ProgTrack is an online web app that allows teachers and students to keep track of student's grades and lessons. This project is built for the Advance Algorithm (CSN-501) course project. 

**Group 18**
- Ayush Agarwal (17114017)
- Divyanshu Salve (17114027)
- Twarit Waikar (17114074)

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
$ git clone https://github.com/aagarwal1012/ProgTrack.git
$ npm install
$ cd client
$ npm install
$ cd ..
```

Start the server.

```sh
$ npm start // Starting the server
```

Start the client.

```sh
$ cd client
$ npm start
```

### Database seeding
Database seeding is the initial seeding of a database with data.

```sh
$ node seed.js
```
> seed.js will auto generate some dummy users, lessons and grades. For Users creation faker npm package have been used!
