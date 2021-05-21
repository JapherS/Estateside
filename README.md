![](https://github.com/JapherS/Estateside/blob/master/wiki_image/Estateside_Homepage.png)

# Estateside - A Real Estate Web Application
Team Members: Japher Su, Zoheb Nawaz, Prajakta Dharme, Nicholas Galinski.  
***

## About Project  
The objective of the project was to make a property rental application that would allow users to interactively search properties in the selected area, inspect the different aspects associated with a property like the property type, amenities, parking etc. as well as express their interest in a particular property by contacting the associated property advertiser.  

## Problem Statement  
Two user types that would use this would be those who are looking for a rental (user/client) and those who are renting their unit (host/owner). On the user’s end, they would like to be able to search for properties whereas the owners would be notified of potential buyers.

## Proposed Solution  
Our proposed solution offers a realty web platform for users to browse available realty properties for rent and for sale. Users can search targeted properties and look up the details of the properties of interest. Additionally, the platform allows landlords and agents to update realty information (operations include adding new listings, deleting & modifying existing listings).    

## APIs used  
We are using Zillow’s public APIs. Zillow has a variety of apartment options to buy, sell and rent. The Web API endpoints return JSON metadata about the apartments located in a particular location based on REST principles. We will use the web API to provide search details based on various filters.  
***

# Design

## Architecture and Technology Stack  
Database: MongoDB  
Back End: Java/NodeJS  
Front End: HTML, CSS, Bootstrap, Javascript, Angular 9, React  
Host environment: Heroku  

## UML Diagram
![](https://github.com/JapherS/Estateside/blob/master/wiki_image/Estateside_UML.png)

## RESTful API Endpoints
![](https://github.com/JapherS/Estateside/blob/master/wiki_image/API_Endpoints.png)

## Web Pages and Features
Following is the list of RESTful services listing the URL patterns used to interact with the data model:

![](https://https://github.com/JapherS/Estateside/blob/master/wiki_image/Pages_and_Features_1.png)
![](https://github.com/JapherS/Estateside/blob/master/wiki_image/Pages_and_Features_2.png)
***

# Video Demo
[![Overview](https://img.youtube.com/vi/zqbhNCysAUQ/0.jpg)](https://www.youtube.com/watch?v=zqbhNCysAUQ)
[![Overview](https://img.youtube.com/vi/QuAGKK1D6c8/0.jpg)](https://www.youtube.com/watch?v=QuAGKK1D6c8)
[![Overview](https://img.youtube.com/vi/OoB1YM40mc0/0.jpg)](https://www.youtube.com/watch?v=OoB1YM40mc0)
[![Overview](https://img.youtube.com/vi/faO2Kl_NcxM/0.jpg)](https://www.youtube.com/watch?v=faO2Kl_NcxM)
***

# Setup Instructions

## Intellij setup for React-client
1.	Clone the project from https://github.com/JapherS/Estateside
2.	The repository will be cloned in your local directory
3.	Use IntelliJ IDEA or any editors to open the Estateside React project and import all the dependencies 
4.	Add .env.local file which has keys for Google Map and Proxy urls
5.	REACT_APP_GOOGLE_CLIENT_ID={key}
6.	REACT_APP_GOOGLE_MAP_API_KEY={key}
7.	REACT_APP_PROXY_URL=http://localhost:8080 (node server hosting all APIs)
8.	Open terminal in the root folder and perform mvn install to install all dependencies
9.	Run the application from IntelliJ IDEA or through command line using npm start command
10.	The application will run on http://localhost:3000/

## Intellij setup for Node.js server
1.	Clone the project from https://github.ccs.neu.edu/zohebnawaz/estateside-server-node
2.	The repository will be cloned in your local directory
3.	Use IntelliJ IDEA or any editors to open the Estateside Node project and import all the dependencies 
4.	Add .env file which has keys for Google Map and Proxy urls
5.	API_KEY={key}
5.	GOOGLE_CLIENT_ID={key}
5.	GOOGLE_CLIENT_SECRET={key}
5.	DB_URL=http://localhost:8080
8.	Open terminal in the root folder and perform mvn install to install all dependencies
9.	Run the application from IntelliJ IDEA or through command line using node server.js command
10.	The application will run on http://localhost:8080/

## Schema setup
1.	Install mongod
2.	Create a collection for "estateside"
3.	In the project, enter your localhost name, schema name, and password in DB_URL file under .env

Enter URL https://localhost:8080/ in the browser for the server to run.
Enter UEL http://localhost:3000/ in the browser. This opens the Estateside application on your local host!






