# rds-mysql

Project: Setting up an Amazon RDS with MYSQL engine




Objective:To learn how to deplo an AWS Relational Database Services using MYSQL engine






-I logged into my AWS management console.





-Navigated to RDS services





-Clicked on create database and chose MYSQL engine





-I configured the RDS instance settings





-I proceeded to the configure DB instance identifier






-Also the master username and password




-I proceeded to create an EC2 instance





-I proceeded to RDS dashboard to create RDS instance




-I took note of the security group associated to the RDS instance





-I navigated to the EC2 instance dashboard





-on the EC2 I updated the inbound rule of the security group to allow MYSQL traffic




-I now used MYSQL server management studio to connect to the RDS instance using the master username and password




- In the SSMS I created a database using this command (CREATE DATABASE sampledb;)





-I proceeded to use the database to create a table using the command below
USE sampledb;
CREATE TABLE users (
    id INT PRIMARY KEY,
    name VARCHAR(255)
);




-I inserted some data to the table using the below command (INSERT INTO users (id, name) VALUES (1, 'John'), (2, 'Alice');



-I proceeded to perform query using (SELECT * FROM users;)
And the query was successful




The project gave me an insight into the concept of AWS Relational Database Services.





In the process of carrying out this project there were places I got stuck but with the help of the team and the internet, I was able to scale through.




