🧠 Ollama LangChain Memory Chatbot

A conversational AI chatbot built using Streamlit and LangChain, powered by Ollama (LLaMA3.2), and enhanced with conversational memory using ConversationBufferMemory.

This chatbot allows users to interact with a locally hosted LLM while preserving conversation history within a session. Users can also adjust the system behavior using temperature and prompt controls.

🚀 Features

💬 Chat interface built with Streamlit

🧠 Memory-enabled conversations using LangChain

🔁 Reset chat and start over anytime

⚙️ Dynamic system prompt and temperature control

🦙 Uses Ollama with a local model (e.g., llama3.2)

🛠️ Tech Stack

Python 3.9+

Streamlit

LangChain

langchain-ollama

Ollama (Local LLM backend)

📦 Installation

1. Clone the Repository

git clone https://github.com/your-username/ollama-langchain-chatbot.git
cd ollama-langchain-chatbot

2. Set up a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate       # on Windows: venv\Scripts\activate

3. Install Dependencies

pip install -r requirements.txt





4. Install and Run Ollama

# Install Ollama (https://ollama.com/download)
ollama run llama3:instruct     # Or any model like llama3.2

🔁 Make sure the model name used in your code matches the one downloaded.

▶️ How to Run

Once dependencies are installed and Ollama is running:

streamlit run app.py

Replace app.py with your actual filename if it's different.

⚙️ App Usage

Adjust the temperature in the sidebar for more creative or more deterministic responses.

Edit the system prompt to change how the chatbot behaves.

Click 🔄 Reset Chat to clear the memory and start a fresh conversation.

Use the chat input box to converse with the bot in real-time.

