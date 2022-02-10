# E-commerce Back End
A back end for an e-commerce website that uses the latest technologies

## Install Dependencies
```bash
npm install
```

## Setup .env file
Create `.env` file at the root with following content:
```bash
DB_NAME='ecommerce_db'
DB_USER='FILL THIS'
DB_PW='FILL THIS'
```

## Create Your Database
Use the schema.sql file in the db folder to create your database using MySQL shell commands.
```bash
source db/schema.sql
```

## [OPTIONAL] Seed with Test Data
```bash
npm run seed
```

## Start the Server
```bash
npm start
```
Then you will be able to access the server at http://localhost:3001