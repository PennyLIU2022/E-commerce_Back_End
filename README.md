# E-commerce Back End
This is the back end for an e-commerce site, working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

## Table of Contents
  * [User Story](#user-story)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Walkthrough Video](#walkthrough-video)
  * [Questions](#questions)  

## User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Installation
- This application need a node.js, the installation details can be found at [offical website](https://nodejs.org/en/download/).
- This application also need to install mysql, please refer to [mysql website](https://www.mysql.com/downloads/) for details.
- Install required node pacakges by running:
    ```bash
    npm i
    ```
- Create schema of database tables by running the sql query in ```db``` folder.
    ```
    source db/schema.sql
    ```
- Seed data to your database by running
    ```
    npm run seed
    ```
- Sync the Sequelize models to the MySQL database by running
    ```
    npm start
    ```

## Usage
A manager can:
- View all products, categories, tags
- View a product/category/tag by its id value
- Add a new product/category/tag
- Update a product/category/tag
- Delete a product/category/tag

## Walkthrough Video
[E-commerce Back End Video](https://drive.google.com/file/d/1UWDrVCMpXh2wRQV44WbVEPAobiCxoSeo/view)

## Questions
If you have any questions, you can find [my Github](https://github.com/PennyLIU2022) and reach me by email at: pennyliu@gmail.com