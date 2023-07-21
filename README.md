# E Commerce Back End Mod 13

### Table of Contents

- [NPM](#npm)
- [User Story](#user)
- [Install](#initialize)
- [Contributing](#contributing)
- [Questions](#questions)
- [About](#about)
- [Screenshot](#screenshot)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## NPM Packages
- mysql2 https://www.npmjs.com/package/mysql2
- sequelize https://www.npmjs.com/package/sequelize
- express.js https://www.npmjs.com/package/express
- bcrypt https://www.npmjs.com/package/bcrypt


## How To Initialize Application

1. Clone the repo.
2. To install the npm packages and make edits to the code, run "npm install express sequelize mysql2 bcrypt" in the terminal.
3. Create a .env file with the following syntax...

```md
DB_NAME='ecommerce_db'
DB_USER='your_username'
DB_PW='your_msqlpwd'
```

4. Log into your MySQL shell and create the db by running 'source db/schema.sql'
5. After you create the db, you can exit and run "npm run seed" in your terminal to seed the db with data.
6. Start the app with "npm start" and use the Insomnia Core (preferable) to test the routes.

## Author

Luis Pardo


## Screenshot

Pending
