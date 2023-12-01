# Chatbot_usingPython
A chatbot is an instant messaging account that able to provide services using instant messaging frameworks with the aim of providing conversational services to users in an efficient and friendly manner. In technological view it is a set of queries, that contains predefined questions and answers leveraging Natural Language Processing (NLP). 

1.	PROBLEM STATEMENT

Chatbot to perform operations like greet the user, tell the current date time and day, predict the weather forecast of the city selected of users choice, text to speech operation.  

2.	OBJECTIVES
•	Develop a basic chatbot that can interact with users and respond to their queries.
•	Implement greetings functionality to greet the user with random responses.
•	Provide the chatbot with a name and allow users to inquire about its name.
•	Enable the chatbot to provide the current date and time upon user request.
•	Allow the chatbot to inform the user about the current day of the week.
•	Handle user expressions of gratitude and respond with appropriate acknowledgments.
•	Incorporate a well-being check to allow users to ask how the chatbot is doing and respond positively.
•	Integrate weather forecasting functionality to provide weather information for a specified city.
•	Implement a text-to-speech feature using the pyttsx3 library to enable the chatbot to speak.
•	Allow users to engage in a conversation with the chatbot, listening to its spoken responses.
•	Provide the chatbot with the ability to generate random responses for different types of user inputs.
•	Handle unrecognized user inputs and prompt the user to try again.

3.  MODULES USED IN THIS PROJECT:

a)Python - Random Module:
    The random module is a built-in module to generate the pseudo-random variables. It can be used perform some action randomly such as to get a random number, selecting a random elements from a list,                shuffle elements randomly, etc.
    Syntax: import random
b)Python-Date time module:
    In Pyhton, date and time are not a data type of their own,but a module named datetime can be imported to work with the date as well as time.Python Datetime module comes built into python,so there is no need      to install it externally.
    Syntax:  import datetime
Print(datetime.datetime.now())
c)  . Python -requests module:
    Requests library is one of the integral part for making HTTP requests to a specified URL. When one makes request to a URL, it returns a response. Python requests provides inbuilt functionalities for managing     both the request and the response.
    Syntax:
    import requests 
    requests.ger(url,params={key:value},args)
d)  Pyhton pyttsx module:
    pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline and is compatible with both Python 2 and 3. An application invokes the pyttsx3.init() factory function     to get a reference to a pyttsx3. Engine instance. it is a very easy to use tool which converts the entered text into speech. The pyttsx3 module supports two voices first is female and the second is male         which is provided by “sapi5” for windows. It supports three TTS engines.
    Syntax: import pyttsx3
    All these above modules have to be installed in the command prompt of our system and then use it in our program.

4. CONCLUSION

In this project, we have introduced a chatbot that is able to interact with user. This chatbot can answer queries in the textual user input. For this purpose, random() module has been used. The chatbot can answer only those questions which he has the answer in the list created for a particular question and selects one answer randomly and gives it as output. So, to increase the knowledge of the chatbot, we can add the  Sports, News, Government and a lot more using the requests module and get the result from the internet. The next step towards building chatbots involves helping people to facilitate their work and interact with computers using natural language or using their set of rules.

