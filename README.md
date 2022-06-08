# Ecommerce-Back-End

## Table of contents

> - [Title / Repository Name](#title--repository-name)
>   - [Table of contents](#table-of-contents)
>   - [About / Synopsis](#about--synopsis)
>   - [Features](#features)
>   - [Usage](#usage)
>   - [Installation](#installation)
>   - [Technology](#technology)
>   - [Credits](#credits)
>   - [Contributing / Reporting issues](#contributing--reporting-issues)

## About / Synopsis

- Ecommerce-Back-End was created as a bootcamp project to explore building a back-end for an e-commerce site using a working Express.js API and configuring it to utilize [Sequelize](https://www.npmjs.com/package/sequelize) to interact with a [MySQL](https://www.npmjs.com/package/mysql) database.

- Ecommerce-Back-Ends CRUD methods (POST, GET, PUT, and DELETE) were tested using [Insomnia](https://docs.insomnia.rest/), both for its utility in testing such routes, and as an opportunity to learn more about the tool.

- If you would like to watch a demo of Ecommerce-Back-End via Screencastify, click [here,](https://drive.google.com/file/d/1mvVvZmgX-lAfOqaj__JtELKIqDFhxaYx/view) or watch on YouTube [here.](https://youtu.be/R1bEIM8DHBQ)
  - Video runtime is 8 minutes and 29 seconds.

## Features

    - Create new Categories, Products, and Tags
    - Edit prices, stock, prodcut names, product Tags, and product Catgories
    - Look-up Products, Categories, and/or Tags as a group, or individually
    - Delete Categories, Products, and Tags as needed

### Usage

![Eccomerce database tables](assets/images/ecommercedbtables.png?raw=true)
![Seeded database](assets/images/ecommerceseededdb.png?raw=true)
![Testing in Insomnia](assets/images/ecommerceinsomniatesting.png?raw=true)

## Installation

- Clone this repository.
- run npm install in the Devlop directory.
- Add and edit .env file to your specific configuration.
- Create your database by running "source db/schema.sql" from the MySQL shell.
- Run "node seeds/index.js" at the command line if you wish to further test with provided database.
- Start server and connect to database by running "npm start" at your command line.

## Technology

Ecommerce-back-end was created utilizing the following:

- [Visual Studio Code](https://code.visualstudio.com/)
- [MySQL](https://www.npmjs.com/package/mysql)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Insomnia](https://docs.insomnia.rest/)
- [Express.js](http://expressjs.com/)

## Credits

- [Insomnia Help](https://dev.to/kmcknight91/how-to-use-insomnia-to-test-api-endpoints-1lad)
- [MySQL Help](https://www.javatpoint.com/mysql-commands-cheat-sheet)
- [README guide](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
- [Musical inspiration](https://www.youtube.com/watch?v=_nSalXeU11Y)

## Contributing / Reporting issues

- Ecommerce-Back-End was created as a [boot camp](https://bootcamp.berkeley.edu/coding/) project. If you are interested in contributing, or have questions about this project, please contact me [here.](mailto:stokescomp01@gmail.com)
