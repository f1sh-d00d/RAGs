This version of the app is a RAG Streamlit chat that has a decision agent to provide the best response to you. When you enter a query, the agent will compare the response of of llama3.2 directly to the file-augmented llama3.2 response and provide the more accurate/relevant answer. This allows you to ask questions, and get responses, from beyond the scope of the uploaded file.

This program assumes you have llama 3.2 installed

To run the app, do the following:

1. In a terminal window, move into the project folder above where you are storing this app

2. Run the command 'pip install -r requirements.txt'
	- You will only need to run this command before you run the website for the first time.

3. Open a seperate terminal window and run the command "Ollama serve"
	- If you get the error  "Error: listen tcp 127.0.0.1:11434: bind: address already in use", then you can proceed to the following steps. Just ignore the error

4. Return to the terminal window where you are in the project folder

5. Run the command 'streamlit run app.py'
	- You will then be taken to the app website where you can interact with the model.

