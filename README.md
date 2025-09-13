Of course. Here is a complete GitHub README file for your project, formatted in Markdown. You can copy and paste this directly into your `README.md` file on GitHub.

-----

# LangGraph: Build Stateful Agentic AI Graph

This project demonstrates a sophisticated, stateful AI agent built using **LangGraph**. The application serves as an intelligent news aggregator and summarizer, capable of performing complex tasks like tool calling, data structuring, and generating dynamic summaries based on user queries.

The user interface is built with **Streamlit**, providing a clean and interactive way to engage with the AI agent.

## ✨ Key Features

  * **Stateful Agentic Architecture**: Utilizes LangGraph to create agents that maintain memory and state across interactions.
  * **Dynamic Tool Calling**: The agent can autonomously decide to use tools (e.g., a news API) to fetch real-time, relevant information.
  * **Multi-LLM Support**: Easily switch between different Large Language Models like **Groq, Llama, Gemini**, and others.
  * **Structured Data Output**: The agent can process unstructured data from the web and present it in a clean, structured format like a table.
  * **On-Demand News Analysis**: Provides various views of news data, from high-level summaries to detailed weekly digests.

-----

## 🚀 Application Showcase

Here are a few snapshots of the agent in action, demonstrating its different capabilities.

### 1\. Basic Conversational Summary

The agent provides a concise, high-level summary of the latest news, covering key events in different regions and topics.

![Basic Chatbot ](<Screen Shorts/Basic Chatbot.png>)


### 2\. Agent with Tool Calling & Structured Output

This view shows the agent's "thought process." It starts by executing a **Tool Call** to fetch raw data. It then processes this information and presents the most critical news in a structured, easy-to-read table.

![ Chatbot with tool call ](<Screen Shorts/Chatbot with tool call.png>)


### 3\. Weekly News Explorer

The agent can generate a curated summary of news for specific periods, complete with headlines and source links, allowing users to catch up on the week's events at a glance.

![Chatbot with weekly news summary](<Screen Shorts/Chatbot with weekly news summary.png>)

-----

## 🛠️ Technology Stack

  * **Core Logic**: LangGraph, LangChain
  * **Frontend**: Streamlit
  * **LLMs**: Google Gemini, Llama, Groq
  * **Programming Language**: Python

-----

## ⚙️ Setup and Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up environment variables:**

      * Create a file named `.env` in the root directory.
      * Add your API keys to this file. For example:
        ```
        GOOGLE_API_KEY="YOUR_GOOGLE_API_KEY"
        GROQ_API_KEY="YOUR_GROQ_API_KEY"
        ```

5.  **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

-----

## 📖 How to Use

1.  Open the application in your browser (usually at `http://localhost:8501`).
2.  From the sidebar, select the **LLM** you wish to use.
3.  Enter the required **API Key**.
4.  Choose one of the available functions, such as **"Basic Chatbot"** or **"AI News Explorer"**.
5.  Interact with the agent by typing in the message box or clicking the provided buttons.