# 🧠 Ollama‑based LangChain Chatbot

A conversational AI chatbot built with **Streamlit**, **LangChain**, and **Ollama (LLaMA3.2)** that remembers chat context within a session using LangChain’s `ConversationBufferMemory`.

This project offers:
- Interactive chat interface
- Adjustable system behavior and temperature
- Chat memory within the session
- Option to reset the conversation

---

## 🚀 Repository

**GitHub**: [Krish‑jain20/Ollama‑based‑Langchain‑Chatbot](https://github.com/Krish-jain20/Ollama-based-Langchain-Chatbot.git)

---

## 🛠️ Tech Stack

- **Python 3.9+**  
- **Streamlit** – For the web UI  
- **LangChain** – For LLM orchestration and memory  
- **langchain-ollama** – Ollama integration with LangChain  
- **Ollama** – For local LLM inference (e.g., LLaMA3.2)

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Krish-jain20/Ollama-based-Langchain-Chatbot.git
cd Ollama-based-Langchain-Chatbot
```
### 2. Set up a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```


### 4. Install and run Ollama
Download Ollama from [https://ollama.com/download](https://ollama.com/download)

Start the LLM model (e.g., llama3:instruct):
```bash
ollama run llama3:instruct
```
🔁 Ensure the model name used in your code matches the one available on your system (llama3.2, llama3:instruct, etc.)

### ▶️ How to Run
Once dependencies are installed and Ollama is running:
```bash
streamlit run app.py
```
Replace `app.py` with your actual filename if different.

### ⚙️ App Usage
In the Streamlit sidebar:
- 🎛️ **Temperature**: Controls creativity vs. determinism of the LLM.
- 🧠 **System Prompt**: Defines how the AI should behave (e.g., teacher, assistant).
- 🔄 **Reset Chat**: Clears the current conversation memory.

In the chat area:
- 🗨️ Enter any question or prompt.
- 🧵 The chatbot will respond while remembering prior context from the session.
