# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

## Description

Build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Video Walkthroughs

**Products Demo in Insomnia**
<media\Products Video Walkthrough Insomnia.webm>
**Link to MyDrive:**<https://drive.google.com/file/d/1nfImGmEhRy0fu0p4uhHjSYQDzr7-5kmd/view>

**Categories Demo in Insomnia**
<media\Categories Video Walkthrough Insomnia.webm>
**Link to My Drive:**<https://drive.google.com/file/d/1Q3uNUJRf-IO9-20USU_MfbW57A01HzvM/view>

**Tags Demo in Insomnia**
<media\Tags Video Walkthrough insomnia.webm>
**Link to MyDrive:**<https://drive.google.com/file/d/1B1xFe3RzArfzrXqsveCFUvkVCND4qAsv/view>

## USER STORY

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies.

## ACCEPTANCE CRITERIA

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database.