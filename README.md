# [Hexawar.io](https://hexawar.io)

![Release](https://img.shields.io/badge/Release-v1.0-blueviolet)
![Language](https://img.shields.io/badge/Language-JavaScript-ffcc14)
![Frameworks](https://img.shields.io/badge/Frameworks-NodeJS_Socket.io-00cf2c)
![Size](https://img.shields.io/badge/Size-3Mo-f12222)
![Open Source](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)

<br/>

This project is a massively multiplayer game that runs directly on the browser, it takes up the concept of *.io* games: everyone plays on a large map and the goal is to be the first of the global ranking. It is a simple land capture game where you can attack other territories with your troops.

<br/>

<p align="center">
	<img src="https://github.com/DarioNonis/Hexawar.io/blob/main/resources/misc/hexawar_logo.svg" width="500">
</p>

<br/>

# Summary

* **[Summary](#summary)**
* **[How to play?](#how-to-play)**
* **[Install](#install)**
	* [Dependecies](#dependecies)
	* [Setup](#setup)
* **[Credits](#credits)**

<br/>

# How to play?

* First, choose a name and a color (or a skin if you had any) for your player.

* Then, you will get a cell in the map, this 10 troops.

* You can use theses troops to expend your territory, by clicking on cells around you.

* You can also use them to attack other players and beat them in the global ranking.

# Install

## 1/ Dependecies

* **[NodeJS](https://nodejs.org/en/)**
* **[npm](https://www.npmjs.com)**
* **[MongoDB](https://www.npmjs.com)**

**Windows :**

* NodeJS and npm : **[install here](https://nodejs.org/en/download/)**.
* MongoDB : **[install here](https://www.mongodb.com/try/download/community)**.

**Unix :**
```shell
$ sudo apt install nodejs
$ sudo apt install npm
$ sudo apt install mongodb
```

## 2/ Setup

* Add a file named `.env` in the root of the project with :
```shell
TOKEN_SECRET=<random long string>
MONGODB_URL=<your mongodb url>/hexawar
MONGODB_USER=<user> #optional
MONGODB_PASSWORD=<password> #optional
```

* Install the dependencies with `npm install`

* Compile typescript files with `npm run build` *(or `npm run devBuild` for real time compilation)*

## 3/ Run

**Default :**

```shell
$ npm run start
```

**Dev :**

```shell
$ npm run dev
```

**Server :**

```shell
$ npm run fstart
```
(Stop the server with : `npm run fstop`).

<br/>

# Credits

* [**Dario Nonis**](https://github.com/DarioNonis) : Creator of the project.
