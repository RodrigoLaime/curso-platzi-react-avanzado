##
npm i webpack webpacl-cli --save-dev

## enpaketa el proyecto 
en la temrminal
./node_modules/.bin/webpack ./src/index.js

## plugin html
npm i html-webpack-plugin --save-dev

## servidor de webpack
npm i webpack-dev-server --save-dev

## react
npm i react react-dom

## babel
npm i @babel/core @babel/preset-env babel-loader --save-dev

npm i @babel/preset-react --save-dev

##
$ npm i standard --save-dev
npm install -g vercel


    "name": "petgram-server-rodrigoL",

apollo-server-express  MISSING   2.5.0  3.12.0  -         api       
bcrypt                 MISSING   3.0.6   5.1.0  -         api       
cors                   MISSING   2.8.5   2.8.5  -         api       
express                MISSING  4.17.0  4.18.2  -         api       
express-jwt            MISSING   5.3.1   8.4.1  -         api       
graphql                MISSING  14.3.0  16.6.0  -         api       
jsonwebtoken           MISSING   8.5.1   9.0.0  -         api       
lowdb                  MISSING   1.0.0   5.1.0  -         api       
uuid  

"apollo-server-express": "^3.12.0",
"bcrypt": "3.0.6",
"cors": "2.8.5",
"express": "^4.18.2",
"express-jwt": "^8.4.1",
"graphql": "14.3.0",
"jsonwebtoken": "^9.0.0",
"lowdb": "1.0.0",
"uuid": "3.3.2"


{           
            "src": "index.js",
            "use": "@vercel/node"
        }
