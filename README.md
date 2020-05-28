						Assignment For Rentomojo
										-Saransh Jain
PHONE BOOK WEB APPLICATION
## About
It is a simple Node Express Web Application using MySQL as its Database.

## Description
1.  It will ask you for the Database host, password. To login in a login page.
2.  After you connect it with the database it will show you the features, like :
    i.      Adding a Phone Number
    ii.     Deleting a phone number
    iii.    Updating a phone number
    iv.     Searching a phone number

## Install All the Dependencies
```
npm i
```

## Connect to the Database
You must have to connect this application to your MySQL Database using environment variables

## Create Tables
You have to create two tables. I have added the commands below so that yoy can create those tables yourself
### User Table:
```
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(100) NOT NULL,
  password VARCHAR(100) NOT NULL
);
```
### Phones Table:

CREATE TABLE phones (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(250) NOT NULL,
  phone VARCHAR(100) NOT NULL,
  user_id INT NOT NULL,
  FOREIGN KEY(user_id) REFERENCES users(id)
);
```

## Run development server
```
npm run dev

## Thanks

```
||||||||||| |||     |||    |||    |||   ||| |||  || ||||||||
    |||     |||     |||   |||||   ||||| ||| ||| ||   |||
    |||     |||||||||||  ||| |||  ||| ||||| |||||     |||
    |||     |||     |||  ||| |||  |||  |||| ||| ||      |||
    |||     |||     ||| |||   ||| |||   ||| |||  || ||||||||
```
