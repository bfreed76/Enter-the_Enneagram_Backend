# Enter the Enneagram Backend


See the working app and [discover your Enneatype!](https://enter-the-enneagram.herokuapp.com/)

 
<p align="center">
<img src="./public/i_screenshot1.jpg" alt="screenshot">
</p>

## Description

This app uses React, HTML and CSS on the frontend and JSON server to provide a simple, RESTful backend. 

Please note that this repository contains the backend for Enter the Enneagram. [The  frontend can be found here.](https://github.com/bfreed76/Enter-the-Enneagram)

![Heroku](https://heroku-badge.herokuapp.com/?app=heroku-badge)

### Built Using

[![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)](https://reactjs.org/) [![ReactRouter](https://img.shields.io/badge/ReactRouter-4F545E?style=flat&logo=reactrouter)](https://reactrouter.com/) ![JSON-server](https://img.shields.io/badge/JSON%20Server-green?style=flat&logo=json) ![React-ChartJS-II](https://img.shields.io/badge/ChartJS%20II-pink?style=flat&logo=react)

<p align="center">
<img src="./public/i_screenshot2.jpg" alt="screenshot">
</p>

<!-- CONTACT -->
## Contact Me

[![Linkedin Badge](https://img.shields.io/badge/-brintonfoyreed-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/brintonfoyreed/)](https://www.linkedin.com/in/brintonfoyreed/) [![Instagram Badge](https://img.shields.io/badge/-nigels_vacation-purple?style=flat-square&logo=instagram&logoColor=white&link=https://www.instagram.com/nigels_vacation/)](https://www.instagram.com/nigels_vacation/) [![Medium Badge](https://img.shields.io/badge/-brintonfoyreed-03a57a?style=flat-square&labelColor=000000&logo=Medium&link=https://brintonfoyreed.medium.com/)](https://brintonfoyreed.medium.com/)[ ![Gmail Badge](https://img.shields.io/badge/-brintonfoyreed@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:brintonfoyreed@gmail.com)](mailto:brintonfoyreed@gmail.com)

Project Link: [Enter the Enneagram](https://enter-the-enneagram.herokuapp.com/)

<a href="https://github.com/bfreed76">
<strong>See more apps on my profile page »</strong></a>

<p align="center">
<img src="./public/i_screenshot4.jpg" alt="screenshot">
</p>

## To start Enter the Enneagram backend 

Start JSON server in the root directory terminal:
```
node server.js
```
Please note that the React server on the frontend must be initialized separately. 

[Follow frontend setup instructions here.](https://github.com/bfreed76/Enter-the-Enneagram)

## Requirements

- NodeJS (v14 or higher) and NPM
- JSON Server 0.16.3 or higher

See Environment Setup below for instructions on installing these tools if you
don't already have them.

## Environment Setup

<p align="center">
<img src="./public/i_screenshot5.jpg" alt="screenshot">
</p>

### Install NodeJS

Verify you are running a recent version of Node with:

```sh
node -v
```

If your Node version is less than 14, update it with:

```sh
nvm install node
```

You can also update your npm version with:

```sh
npm i -g npm
```

### Install JSON Server

```
npm install -g json-server
```

### Start JSON Server

```bash
json-server --watch db.json
```

One the server is running, if you visit https://localhost:3000 in your browser (or Postman, Insomnia, etc.), you will see the contents of the db.json file.

## Please note that this repository contains the backend for Enter the Enneagram. [The frontend can be found here.](https://github.com/bfreed76/Enter-the_Enneagram)