# Human Resources Chatbot

In this project, I've tried to implement a chatbot that tends to behave and respond like an HR representative. An employee or user can ask this bot basic queries related to HR like:

1. How many days off are allowed?
2. What is the company policy on paternity leave?
3. What benefits do I get? 
& so on...

To train the bot, I've implemented a basic feed forward neural net which is trained on some custom data that I made. 

For frontend deployment, I've made use of Flask and Javascript to basically link the chat UI with the model so that the user can get appropriate responses according to their queries by the model within the chat interface. 

## Get started

clone the repo

`git clone https://github.com/mihir224/H.R.-Chatbot`

## Model

Install the required packages through 

`pip install <package-name>`

Then, run the app.py file, this will host the model on a local host as a backend service.

I recommend using PyCharm IDE for ease of use.

## Frontend

You can directly run the base.html in your browser, JavaScript will start sending the user queries to the model and the appropriate responses from the model will then be retrieved and shown in the chat.
