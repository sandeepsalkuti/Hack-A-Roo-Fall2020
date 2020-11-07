# Hack-A-Roo-Fall2020

# Introduction:

A chatbot is an application which can initiate and continue a conversation using auditory and/or textual methods as a human would do. A chatbot can be either a simple rule-based engine or an intelligent application leveraging Natural Language Understanding. It is usually used in different fields like customer support, appointment booking, frequently asked questions etc. 
This application is built using HTML, CSS, Python, Flask and RASA. Rasa is an open source machine learning framework for building contextual AI assistants and chatbots. 

Rasa has two main modules:
•	NLU for understanding user messages 
•	Core for holding conversations and deciding what to do next 

# Installations and working procedure:

Install Rasa (command pip install rasa) and spacy library (command pip install spacy ). Initialize Rasa project using “Rasa init” and edit files accordingly as per user needs.

Nlu.md: This file is used to create all the intents and their sample utterances for conversation.
Domain.md: This file is used to configure the bot responses.
Stories.md: This file is used to create the conversation flows.

•	enter the command ‘rasa train’ to train the model with new conversation elements.
•	enter the command ‘rasa test’ to test and check accuracy how well it is performing.

Run the chatbot by enabling it as API (rasa run -m models --enable-api --cors "*" –debug) and consume that API in the front end to display bot in webUI for this consumed react based chat room component for rasa stack. Run front end part using “python manage.py runserver” command.  
Navigate to http://127.0.0.1:8000/my_app/ where chat bot UI is landed and can start conversation with bot.

# Sample screenshots:

 ![](https://github.com/sandeepsalkuti/Hack-A-Roo-Fall2020/blob/main/images/bot1.JPG)

 ![](https://github.com/sandeepsalkuti/Hack-A-Roo-Fall2020/blob/main/images/bot2.JPG)

 ![](https://github.com/sandeepsalkuti/Hack-A-Roo-Fall2020/blob/main/images/bot3.JPG)
  
 
# References:


Rasa Official documentation https://rasa.com/docs/rasa/user-guide/installation/

https://www.youtube.com/watch?v=XMAw_bKTLbA&t=35s






