![CSUEB Logo](/Images/csueb-logo.jpg)

# BaysBook - Cal State East Bay's very own social media platform

<h1 align="center">
🌐 A MERN Stack Web Application
</h1>

> MERN is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

## Prerequirements

- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

## Clone or download

```terminal
$ git clone https://gitlab.com/software-engineering4/baysbook.git
$ npm i
```

## Running the application on your machine

- After cloning the repo for this project, first run the following command to cd into the root

```terminal
$ cd s2020-ctrlaltelite
```

- from here, package.json contains all the dependencies to run the app, however, they need to be configured locally so in the terminal, first run the following

```terminal
$ npm install
```

- the dependencies for the backend are now configured. From here, in order to run the front end on the server, do the following:

```terminal
$ cd client
$ npm install
```

- you have successfully installed your configurations locally and our node scripts should work. do the following and then the project should automtically open in your default browser. Notice cd .. this means you are going out one directory and back into the project root, where both client side and backend side code live. We can now run the app! Enjoy your experience on Baysbook!

```terminal
$ cd ..
$ npm run-dev
```

## Project structure

```terminal
LICENSE
package.json
server/
   package.json
client/
   package.json
...
```

<h1>Comments</h1>

* This project was developed by myself and 3 other developers in our senior software engineering course. Two students Karan and Omar [social handles will be linked below] were responsible for building the front end while I build the backend and one more student by the name of Aman did QA and assisted me in backend design/development

* This app took us 16 weeks to ship and we worked tremendously as a team. I do not take full credit for this code, as I was an integral part of the team, but not the sole contributor.

* Social Links for my fellow classmates:
   - (Omar Aziz) https://www.linkedin.com/in/omar-aziz-40b715132/
   - (Karan Monga) https://www.linkedin.com/in/karanmongaa/
   - (Aman Verma) https://www.linkedin.com/in/aman-verma3/
   - (Myself) https://www.linkedin.com/in/tanner-barcelos-695619a1/
