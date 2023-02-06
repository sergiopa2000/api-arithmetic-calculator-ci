# Arithmetic Expression Calculator

Rest Api service created on nodejs, user register and login using mongodb (Using mongoose module) as database
and jwt as auth method, token expires after 10 minutes of being generated or after 5 
operations request, being blacklisted on database (Cleans all expired tokens on DB every 8 minutes).

A proxy server is also implemented for request controlling purposes.

It also uses a WebSocket server to control and response client's requests. (Will implement a job queue hopefully soon).

Finally jison lexical parser is used to parse and validate arithmetic expressions.

## Install dependencies
```
npm install
```

## Environment Variables

To run this project, you will need to have some environment variables on your .env file.

Check `.env.example` to get started.

Your cant simply rename `.env.example` file to `.env` and fill it with your things.
<br>
<br>
<br>
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">&nbsp;</img><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"></img>&nbsp;<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"></img>&nbsp;<img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white"></img>&nbsp;<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></img>&nbsp;<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></img>
