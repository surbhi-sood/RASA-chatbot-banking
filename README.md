# RASA-chatbot-banking
Rasa Open Source is an open source conversational AI platform that allows you to understand and hold conversations, and connect to messaging channels and third party systems through a set of APIs. It supplies the building blocks for creating virtual (digital) assistants or chatbots.

Requirements:-
Python 3.7


How it works?
Step 1: Open any Python Compiler of your choice and install Rasa by running the following command in the terminal :-
pip install rasa[full]

This step will take time and will install all the necessary files.

Step 2: Run the command          rasa init--no-prompt        in the virtual environment 

Step 3: If you want to run the basic bot in shell then run the command        rasa shell 
once done your chatbot will be ready for interactions

Step 4 : Once you have developed your bot and you are ready to integrate the bot with the UI, you can start the Rasa server using the below command

rasa run -m models --enable-api --cors "*" --debug

Step 5 : Access the index.html page after running step 4 and start your interactions with the chatbot


note: after step 2 you can check for the changes needed in the folder related to the chatbot .
