# E-Commerce-Back-End


## Description 
Applicaton that uses Sequlize to create back end of an e-commerce

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Demo](#Demo)
* [Credits](#credits)

## Installation 
* Clone the repo
* After opening up the application  type ```npm install``` into the terminal
* From the root of the folder create a ```.env``` file and enter 
```
DB_NAME = ecommerce_db
DB_USER = (your SQL user name goes here)
DB_PW = (your SQL password goes here)
```
* In the terminal run ```mysql -u(your user name goes here) -p``` which you will then see a prompt to type in your mysql password.
* Then run ```source db/schema.sql``` after this takes effect run ```quit``` to exit out of the mysql terminal back into bash.
* To seed test run ```npm run seed ``` in the terminal.
* Start the server by running ```npm start``` the terminal should now say ```App listening on port 3001!```
* Open up the application Insomnia and test the server using```http://localhost:3001/api/```
* ```GET``` and ```POST``` at ```api/categories``` ```api/products``` ```api/tags```
* ```GET``` ```PUT``` ```DELETE``` at ```api/categories/:id``` ```api/products/:id``` ```api/tags/:id```


## Demo
[How to get started and install application](https://drive.google.com/file/d/1LvvhgUDJD0OxSbSLH1M-UF6qWmfSAr4r/view)

[Testing out ```GET``` and ```POST``` in Insomnia](https://drive.google.com/file/d/1ofxm4PTEGlL-yigjecPtFG082UWbqlxq/view)

[Testing out ```PUT``` and ```DELETE``` in Insomnia](https://drive.google.com/file/d/1_n7sevo32Jm0crSQXixfCmm2fVjl9sgk/view)


## Credits
* Starter code provided by [UCF Coding BootCamp](https://github.com/coding-boot-camp/fantastic-umbrella)
* Coded by Jessica Coneff
