# Personal-Assistant
What can this A.I. assistant do for you?
•	It can send emails on your behalf.
•	It can play music for you.
•	It can do Wikipedia searches for you.
•	It is capable of opening websites like Google, Youtube, etc., in a web browser.
•	It is capable of opening your code editor or IDE with a single voice command.
Starting VS Code
I am going to use the VS Code IDE in this video. Feel free to use any other IDE you are comfortable d with. Start a new project and make a file called jarvis.py.
What is pyttsx3?
•	A python library that will help us to convert text to speech. In short, it is a text-to-speech library.
•	It works offline, and it is compatible with Python 2 as well as Python 3.
What is sapi5?
•	Microsoft developed speech API.
•	Helps in synthesis and recognition of voice.
What Is VoiceId?
•	Voice id helps us to select different voices.
•	voice[0].id = Male voice 
•	voice[1].id = Female voice
Defining Task : To send Email
To send an email, we need to import a module called smtplib.
What is smtplib?
•	Simple Mail Transfer Protocol (SMTP) is a protocol that allows us to send emails and to route emails between mail servers. An instance method called sendmail is present in the SMTP module. This instance method allows us to send an email.  It takes 3 parameters:
•	The sender: Email address of the sender.
•	The receiver: T Email of the receiver.
•	The message: A string message which needs to be sent to one or more than one recipient.
