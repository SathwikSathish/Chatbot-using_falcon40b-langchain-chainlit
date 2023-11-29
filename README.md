# Chatbot-using_falcon40b-langchain-chainlit
This is an application powered by one of the most powerfull open-source LLM -Falcon-40B which is built using Langchain which is deployed on Chainlit, a lightweight web application framework, to effortlessly deploy and manage our chatbot.

Chat UI using Falcon 7B, LangChain and Chainlit
Chatbot in this respository is created using LangChain Framework, Open source Falcon 7B Instruct model and ChainLit. API of open source LLM is taken from Hugging Face Hub. Deployment is done using ChainLit which provides great Aesthetic UI for AI to user communication.

This repository can run in Github codespaces or locally. Please add your huggging face API token and input it in .env (Rename example.env to .env). After running 'requirements.txt' please run following command to start the chat UI:

chainlit run langchain_falcon.py -w
