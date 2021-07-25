# Unit 11 Express Homework: Note Taker

![GitHub license](https://img.shields.io/badge/Made%20by-%40cartaya1-orange)
![GitHub license](https://img.shields.io/badge/license-ISC-blue.svg)

# Description :

This is a simple Note Taker application that allows users to add, view saved notes and also delete the notes if the user don't need that note anymore. This application uses an express backend and save and retrieve note data from a JSON file.

Esta es una aplicación simple para tomar notas que permite a los usuarios agregar, ver notas guardadas y también eliminar las notas si el usuario ya no necesita esa nota. Esta aplicación utiliza un backend rápido, guarda y     recupera datos de notas de un archivo JSON.

## Deployed Application :
[Note Taker](https://cartaya1-note-taker.herokuapp.com/)

# Table of Contents
* [Demo](#demo)
* [Technology](#technology)
* [Usage](#usage)
* [Features](#features)
* [License](#license)
* [Contribution](#contribution)
* [Questions](#questions)
* [Repository Link](#Repository)
* [GitHub Info](#GitHub)

# User Story

```
AS A user, I want to be able to write and save notes.

I WANT to be able to delete notes I've written before.

SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

```
COMO usuario, quiero poder escribir y guardar notas.

QUIERO poder borrar notas que he escrito antes.

PARA QUE pueda organizar mis pensamientos y realizar un seguimiento de las tareas que debo completar
```

# Business Context

* For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. 

* Being able to take persistent notes allows users to have written information available when needed.

* Para los usuarios que necesitan realizar un seguimiento de una gran cantidad de información, es fácil olvidar o no poder recordar algo importante.

* Poder tomar notas persistentes permite a los usuarios tener información escrita disponible cuando sea necesario.

# Demo :
![Note Taker](public/assets/images/NoteTaker.gif)

# Application Preview : 

|Main Page|Saved Notes|Delete Note
|--|--|--
|![Main Page](public/assets/images/NoteTaker.png)|![Saved Notes](public/assets/images/SavedNotes.png)|![Delete Note](public/assets/images/DeleteNote.png)

# Technology :

**1. [Express.js](https://expressjs.com/)** :

* Web Applications : Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

* APIs : With a myriad of HTTP utility methods and middleware, creating a robust API is quick and easy.

* Performance : Express provides a thin layer of fundamental web application features, without obscuring Node.js features.

**2. [Node.js](https://nodejs.org/en/)** : 

* Node.js is an open-source and cross-platform JavaScript runtime environment. 

* A Node.js app is run in a single process, without creating a new thread for every request. 

* Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking.

**3. [uuid](https://www.npmjs.com/package/uuid)** : Creates random unique id's.

# Usage :

* Clone this repository to use this application on local machine.

* To install necessary dependencies, run the following command :

```
npm i
```

* The application will be invoked with the following command: This will start localhost server on PORT 3000.

```
node server.js
```

* Open browser and type `http://localhost:3000/` to run this application on your local machine.

# Features :

1. Used 'Express.js' to build server

2. Used 'fs(File System)' module to read and write from 'db.json' file.

3. Used [uuid](https://www.npmjs.com/package/uuid) npm package to give unique id to each note.

4. Application is deployed on [heroku](https://www.heroku.com/) : Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps.

# License

This project is under ![ISC License](https://img.shields.io/badge/license-ISC-blue).

# Contribution

By Luis Cartaya, Pull requests are always welcome!

# Questions
If you have any questions about the repo: 

[Open an Issue](https://github.com/cartaya1/Note-Taker/issues)

[GitHub Email](cartaya1@msn.com)

# Repository
- [Heroku App](https://cartaya1-note-taker.herokuapp.com/)
- [Project Repo](https://github.com/cartaya1/Note-Taker)
- [GitHub Test](https://cartaya1.github.io/Note-Taker/)

# GitHub
- [GitHub](https://github.com/cartaya1) Cartaya's House Inc.