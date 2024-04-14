# CHATBOT_using_Dialogflow
This is a chat bot made using dialogflow for a particular Educational Institution (a university) on their information available.

# How To run this project over any system
FIRST: Clone the Repository to folder to your system.<br>
In the command line run the following commands
1. npm init<br>
2. run npm install express dialogflow body-parser nodemon uuid<br>
   above line (2nd line) will install the dependancies that are required to run the project.<hr>
   
Second: Replace you key file obtained from (dialogflow) in the app.js file, and the project id as well. <br>
i. key file: you can obtain from the service account of dialogflow ES (create key, then download)<br>
ii.project Id: It is your agent Id that would be there in agent general setting of dialgflow.<br>
<hr>
Thrd: Design you intent and respons in the dialgflow <br>
1. The response for a intent  could be written normally and with html tags like <_ol> , <_p> etc.
   so that the response in the custom interface should look clean.<br>
2. TO handle such response the code is also written.<br>

#2 N:B <br>
<ol>
<li>There is code embeded for text-to-speech and speech-to-text feature.But it is not enabled.</li>
<li>If you want you can add this bu reading  the code of index.html file and index.js file . </li>
<li>The app.js file is the node.js server file where the code creates the server locally to run the chat bot.
</li> </ol>

# How to initialize <br>
after completing all the steps <br>
A. run <b> <I>nodemon app </I> </B>in the terminal <br>
B. go to your <B><I>index.html </B> </I> in the file you stored it and open it in browser.<br>
C. There you can give input to the chat bot and get the response.
