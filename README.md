# 🧠 AI Chat Agent

An intelligent conversational AI workflow built using n8n, Google Gemini, SerpAPI, and MongoDB Chat Memory.

This project allows users to chat with an AI agent that can search the web, remember context, and respond intelligently using LLM reasoning.

___🚀 Features___


__✔ Real-time Web Search (SerpAPI)__

The agent can fetch live information from the internet.

__✔ Memory Using MongoDB__

The chatbot remembers:

-previous messages

-conversation context

-last interactions

__✔ Powered by Google Gemini__

Gemini handles:

-reasoning

-natural language responses

-summarization

-answering user queries

__✔ Chat Trigger Support__

The workflow activates automatically when a chat message is received.


___🧩 Workflow Structure___


__Chat Trigger → AI Agent → (Gemini LLM + SerpAPI + MongoDB Memory)__



__1. Chat Trigger__

Starts the workflow when a user sends a chat message.

__2. AI Agent Node__

Coordinates:

-the LLM

-memory

tools (SerpAPI)

__3. Gemini LLM Node__

Generates intelligent replies based on user input.

__4. SerpAPI Tool__

Allows the agent to fetch real-time search results.

__5. MongoDB Chat Memory__

Stores conversation history to maintain context.


__🛠 Tech Stack__

Component	Technology:



| Feature      | Tool          |
|-------------|---------------|
| LLM         | Google Gemini |
| Search      | SerpAPI       |
| Memory      | MongoDB       |
| Automation  | n8n           |
| Integration | Chat Trigger  |



🎥 ___Demo:___

[▶️ Click here to watch the demo] -> https://drive.google.com/file/d/1f8vK_gVxQyovHlGv3SF7gtCzgI6fxWLh/view?usp=sharing
