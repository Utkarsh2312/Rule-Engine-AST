# Rule Engine AST

## Overview

This project is a rule engine system that processes rules and generates an Abstract Syntax Tree (AST). It has a React frontend and a Node.js backend, with a database to store rules.

## Environment setup

- client/.env
- REACT_APP_API_URL=http://localhost:5000/api

- server/.env
- PORT=5000
- MONGO_URI=mongodb://127.0.0.1:27017/ruleEngine

## Project with Docker
- git clone https://github.com/Utkarsh2312/Rule_Engine_AST.git
- cd Rule_Engine_AST

- cd client
- npm install

- cd server
- npm install

- build and start = docker-compose up --build

## Project without Docker

1. Run Frontend:
- cd client
- npm install
- npm start

2. Run Backend:
- cd server
- npm install
- npm start

3. For Database:
-start mongodb server : mongod


