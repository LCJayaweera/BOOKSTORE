Set up File structure

cd backend
npm init -y

add line 
"type": "module", to package.json


install express and nodemon
 npm i express nodemon

change package.json as below,
 "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"

  },