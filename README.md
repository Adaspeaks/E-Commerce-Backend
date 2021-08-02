# E-Commerce-Backend
// Worked on HW with Zach, Chris, Mike and Matt on 07-01-21
## Description

Using Express as the backend and Sequelize to run the no-sql server we are able to simulate a E-Commerce backend. From there we can Create, Read, Update, or Delete items in the backend.

## Table of Contents
* [Installing the dependencies](#Installation)
* [Usage instructions!](#Usage)
* [Contact Info](#Contact)


## License

This project is licensed under the MIT License. To learn more visit:   
> [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)

## Installation

All necessary dependencies can be installed by using

```
npm i
```

into the console.

## Usage
 To use the app sign into the mySql CLI through your prefered terminal. This can be done with the following

 ```
mysql -u root -p password
```
-u and -p signify the fields where you can enter your Username and password for the mysql CLI that was setup on install. If you don't have one of the two or both you may omit them and their following fields.

Seeding the database can be done with the following

```
npm run seeds
```

and finally the entire application can be ran with 

```
node server.js
```

Here's a list of the CRUD routes you can use once the server is up to test functionality

> GET: http://localhost:3001/api/model_route
> POST: http://localhost:3001/api/model_route
> PUT: http://localhost:3001/api/model_route/:id
> DELETE: http://localhost:3001/api/model_route/:id 
> GET by ID: http://localhost:3001/api/model_route/:id

For an indepth demo of me using the application see [Here](https://drive.google.com/file/d/1ng9cfc8uz7QK1gZ6_QzmV4tIwpScZBZG/view)

## Contact
If you have any questions you can reach me at adaspeaks@gmail.com