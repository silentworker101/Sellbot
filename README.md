# Sellbot

![Sellbot](https://github.com/silentworker101/Sellbot/blob/master/Image%202.png)

To run Locally : **npm run dev**

To run Backend : **npm run backend**

To run Frontend : **npm start**

## Google Service Account

*export REACT_APP_GOOGLE_PROJECT_ID="insert google project id"*

*export REACT_APP_DF_SESSION_ID="insert dialogflow session"*

**or**

> Just update the **config.dev** file with your Google Service Account details and **MongoDB** url.

## Dependencies

> Install dependencies in root folder : npm install actions-on-google body-parser dialogflow dialogflow-fulfillment express google-oauth-jwt mongoose --save

>Install  dev dependencies in root folder : concurrently nodemon --save-dev

>Install dependencies in client folder : npm install --save axios materialize-css react react-dom react-router-dom react-scripts universal-cookie uuid --save

>Install  dev dependencies in client folder : npm install --save-dev http-proxy-middleware

## In chatbot:
![](https://github.com/silentworker101/Sellbot/blob/master/Image%203.png)

Type **recommend** me some courses to view the courses offerings.If you say yes in reply, chatbot will ask you some details about you and later it will store your data in the database.

![](https://github.com/silentworker101/Sellbot/blob/master/Image%201.png)


## Deployment link:
[Sellbot Chatbot Heroku App](https://celebal-chatbot.herokuapp.com/)

    
