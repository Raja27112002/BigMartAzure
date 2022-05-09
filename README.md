# BigMartAzure

Nowadays, shopping malls and Big Marts keep track of individual item sales data in order to forecast future client demand and adjust inventory management. In a data warehouse, these data stores hold a significant amount of consumer information and particular item details.

BigMart is a shopping complex which has lot of data about sales and customer, use the data to predict the sales of the stores which helps the stores or shopping complexes to expand their businesses and keep track of their customers favourites and help them to reduce losses in unselling products or keep track of products selling in particular time period. Machine Learning helps them to predict the sales of the stores before they open new stores in desired location

![alt text](https://businessoptions.in/assets/uploads/franchise/gallery/8g8t6begnzezdxsg1zvs.jpg)

In this Project we use the bigmart data preprocess the data and insert the data into machine learning algorithm(RandomForest CLassifier) and tune the hyper parameter to make our model better.

The solution is created in the form of API (Flask) and the frontend has done using HTML and CSS and deployed the Solution in Microsoft Azure

Deployment Process
* Upload my code in Github repository Using Git.
* Login to my Azure Portal and created a Azure App Services
* In that App Services, I created a new resource group for this project 
* Set region to central us and selected a free tier plan for Linux Operating System
* Then I created my Web App
* And I used Deployment center to deploy my web app that present in github using CICD Pipeline
* I have connected my github account and then selected Organization, Repository and Branch that I want to deploy
* By clicking save my webapp started deploying and deployment finished in 
