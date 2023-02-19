# TuringChatBot
A simple chat bot showing deep learning

# Steps for execution
Expose the RASA module at localhost:5000

python -m rasa_nlu.server --path /rasa_version/projects


# In a separate console, execute the following command
python chatbot_api.py

# Now your chatbot is ready to be accessed via API. Try the following:

Call the following API to execute the TFIDF version:
curl http://localhost:5000/version1?query=Can I get an Americano

Call the following API to execute the Rasa version:
http://localhost:5000/version2?query=where is Indian cafe