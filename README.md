# E-commerce Back End Starter Code

### this was made from the starter code we were provided and i finally got around to finishing iverything

### instructions for use
first npm install to get dependency files 
add a .env file to the root and pu in 
-
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'
-
then create schema and seed the db 
run npm start 
demo videos are in google drive showing use of the db though postmate
(https://drive.google.com/drive/folders/1_zqcBGK45gexoHKMEbJBwU8tPxzbU6jy?usp=sharing)

### user story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## acceptance criteria 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database