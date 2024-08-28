This project demonstrates how to build an interactive chatbot using Streamlit and LangChain. The chatbot is equipped with tools to search the web, retrieve information from Arxiv and Wikipedia, and respond to user queries. This project uses the Llama3-8b-8192 model through the Groq API.

Features:

Web Search: Perform searches on the web using DuckDuckGo.

Arxiv Query: Retrieve research papers from Arxiv.

Wikipedia Query: Fetch summaries from Wikipedia.

Interactive Chat: Engage with the chatbot in real-time, with responses displayed directly in the app.

Requirements
Before running the app, ensure you have all the necessary dependencies installed. You can install them using the requirements.txt file provided.

bash
pip install -r requirements.txt


Requirements:

streamlit
langchain
langchain_groq
langchain_community
python-dotenv


Usage:
Enter your Groq API Key: In the sidebar, enter your Groq API key to enable the AI model.

Chat with the bot: Type your questions in the chat input, and the bot will respond with relevant information.

View thoughts and actions: The bot's reasoning and actions are displayed interactively during the chat.
Contributing

Feel free to fork this project and submit pull requests if you'd like to contribute. Contributions are always welcome!

