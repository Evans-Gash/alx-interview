# 0x06. Star Wars API

This project is part of the ALX Software Engineering curriculum, focusing on using the Star Wars API to retrieve and display information about characters from the Star Wars universe.

## General Requirements

- **Allowed Editors**: vi, vim, emacs
- **Interpreted on**: Ubuntu 20.04 LTS using Node.js (version 10.14.x)
- **File Endings**: All files should end with a new line
- **Shebang**: The first line of all files should be exactly `#!/usr/bin/node`
- **README.md**: A README.md file at the root of the project folder is mandatory
- **Code Style**: Your code should be semistandard compliant. Rules of Standard + semicolons on top. Also, reference AirBnB style
- **Executability**: All files must be executable
- **Variable Usage**: You are not allowed to use `var`
- **File Length**: The length of your files will be tested using `wc`

## More Information

### Install Node 10

```bash
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install Semi-Standard

```bash
$ sudo npm install semistandard --global
```

### Install Request Module

```bash
$ sudo npm install request --global
$ export NODE_PATH=/usr/lib/node_modules
```

## Tasks

### 0. Star Wars Characters

Write a script that prints all characters of a Star Wars movie:

- The first positional argument passed is the Movie ID - example: 3 = "Return of the Jedi"
- Display one character name per line in the same order as the "characters" list in the `/films/` endpoint
- You must use the Star Wars API
- You must use the request module

```bash
$ ./0-starwars_characters.js 3
Luke Skywalker
C-3PO
R2-D2
Darth Vader
Leia Organa
Obi-Wan Kenobi
Chewbacca
Han Solo
Jabba Desilijic Tiure
Wedge Antilles
Yoda
Palpatine
Boba Fett
Lando Calrissian
Ackbar
Mon Mothma
Arvel Crynyd
Wicket Systri Warrick
Nien Nunb
Bib Fortuna
```


## Repository Information

- **GitHub Repository**: [Evans-Gash/alx-interview](https://github.com/Evans-Gash/alx-interview)
- **Directory**: [Evans-Gash/alx-interview/0x06-starwars_api](https://github.com/Evans-Gash/alx-interview/0x06-starwars_api)
