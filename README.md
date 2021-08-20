# P0_Restaurants_Analysis

## Project Description
This project aims to analyse restaurants data in different aspects by using NoSql (MongoDB).

## Technologies Used
- Python - version 3.9.5
- MongoDB - version 5.0

## Getting Started
1. Clone the project
```
$ git clone https://github.com/atulgandhi1137/P0_Restaurants_Analysis.git
```
2. Install MongoDB from [Link](https://docs.mongodb.com/guides/server/install/)
3. Install PyMongo [Link](https://pypi.org/project/pymongo/)
```
$ pip install pymongo
```

## Usage
###### Using Mongo shell
1. Start the mongo server 
```
$ 'C:\Program Files\MongoDB\Server\5.0\bin\mongod' --dbpath=<path to store data>
```
2. Start the shell and create a database
```
$ 'C:\Program Files\MongoDB\Server\5.0\bin\mongo'
>>create database restaurants
```
3. Import the json file in restaurant database using mongoimport
```
$ 'C:\Program Files\MongoDB\MongoDBimport\bin\mongoimport' --db restaurants --collection restaurant --type json --file <filename.json>
```
4. Now, Go to Mongo shell and start executing queries

###### Using PyMongo
Once you have the imported json data , you can run PyMongo.py file
