# Addressbook
-------------

A complete example for Spring MVC + Hibernate + Maven CRUD operations.


## Pre-requisites:
-----------------

- JDK 1.5.x or higher  
- Maven 2 or higher  
- set java_home and m2_home  
- Eclipse 3.5 or higher

## How to clone the repo:
--------------------------------

- Open cmd prompt/git bash from windows->start-> run.
- Do a git clone http://ctogitlab.wipro.com/AN843289/addressbook.git

## How to build the project from Eclipse:
-----------------------------------------

- Open up your IDE ( Eclipse ) and go to File -> Import -> General -> Existing maven projects into workspace.  
- import project to eClipse IDE (Existing Projects in Workspace > Browse and locate the extracted "AddressBook" folder).
- Configure Project Build path and add a new Variable "M2_REPO" point to the directory  " <<Local-User-Directory>>/.M2/repository"  
- Go to the project home directory AddressBook, and run 
    - mvn clean package
    - This might take a few seconds to download all the dependencies to your local M2 repo.

## How to run the funtional test cases from Eclipse:
- Run the integration(Selenium) tests (you will need to have Firefox installed):  
	mvn clean integration-test

## How to create the required database schema:
-----------------------------------------------

- Install mysql db with root/root username.
- Execute the addressbook.sql file from your project folder/dbscripts directory.
    - This will create the required schema and table.

## Deploying and Running the application:
---------------------------------

- This project can be deployed on any of the following 
- Tomcat 7x version
- After you create a server, Deploy the project on the server.
- Note: If your IDE does not have the facility to run on an server from within, you can do a mvn package from the command line and deploy the .war file directly on an external server
- Open IE/Chromer and enter the following url  [http://localhost:8080/AddressBook/address](http://localhost:8080/AddressBook/address) to open addressbook application.


## Preview
----------

![](https://github.com/ANVESH1981/javaprogramming/blob/master/addressbook/images/AddressBook.png)

