# Langchain Search Agent with Streamlit UI

This project implements an AI-powered search agent using the Langchain framework and Llama3 large language models through Groq. The system provides a user-friendly interface through Streamlit, allowing users to interact with a chatbot capable of web searches and accessing specialized knowledge bases.

## Features

- Interactive Chatbot: Engages users in conversation and answers queries
- Web Search Capability: Utilizes DuckDuckGo for general web searches
- Specialized Knowledge Access: Integrates Wikipedia and Arxiv for academic and encyclopedic information
- Streaming Responses: Provides real-time feedback as the AI generates responses
- Customizable Settings: Allows users to input their own Groq API key

## How It Works

1. The system initializes with a friendly greeting from the AI assistant
2. Users can input questions or prompts through the chat interface
3. The AI agent processes the input using the Groq language model
4. If needed, the agent uses tools like web search, Wikipedia, or Arxiv to gather information
5. Responses are generated and streamed in real-time to the user interface
6. The conversation history is maintained throughout the session

## Tech Stack Used

- Streamlit
- Langchain
- Groq (Llama3-8b-8192 model)
- DuckDuckGo Search API
- Wikipedia API
- Arxiv API
- Python
- Dotenv


## Note

This project requires a valid Groq API key to function. Ensure you have the necessary credentials before using the application. The search capabilities and response quality depend on the chosen language model and the availability of the integrated APIs.

Sample Output and UI of the Application:
![Sample Output](https://github.com/user-attachments/assets/35f9a853-af5c-46cf-bdce-971f717c9569)
