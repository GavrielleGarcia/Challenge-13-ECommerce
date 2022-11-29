# Challenge-13-ECommerce

## User Story
 ```bash
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Installation
  To install the necessary dependencies, run the following command:
  
```bash
npm i
npm install dotenv --save
npm install express
npm install sequelize sqlite3
npm install --save mysql2
npm install console.table --save
```

After the dependencies are installed, create a .ENV file and fill it with your connection information:
(Don't forget to update your PW)

```bash

DB_NAME='ecommerce_db'
DB_HOST='localhost'
DB_USER='root'
DB_PASSWORD='UPDATE YOUR PASSWORD HERE'

```

Now, you can proceed to create the datbase schema in MySQL Terminal:

```bash
 #under MySQL terminal
    mysql -u root -p
 # to create the DB schema
    db/SOURCE schema.sql
```

Then, start working with the main file:

```bash
  node seeds/index.js
```

## Technologies Used
- MysSQL
- JavaScript
- Node.js
- Insomnia
 

 ## Overview 
 [Link to Overview](https://app.screencast.com/ZPasf540bKof0?conversation=snXTY3snFyCtXjppgx1JI8)

 
## Contributing 
No contributions at the moment, thanks.
 
 
## Questions
  My stuff [gavriellegarcia](https://github.com/gavriellegarcia).

  Send me an owl: gavrielle.garcia@hotmail.com.  