# 🔎 Search-Engine-LLM

This Streamlit application allows users to interact with a chatbot powered by LangChain and Groq's LLMs. The chatbot can search the web using tools like Arxiv, Wikipedia, and DuckDuckGo to provide informed responses.

## Features

- **Interactive Chat Interface**: Engage in a conversational UI powered by Streamlit's `st.chat_input` and `st.chat_message`.
- **Web Search Integration**: Utilize Arxiv, Wikipedia, and DuckDuckGo to fetch real-time information.
- **Streaming Responses**: Experience real-time streaming of responses using `StreamlitCallbackHandler`.
- **Customizable Settings**: Input your Groq API key securely via the sidebar.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ssarthak0/Search-Engine-LLM
   cd Search-Engine-LLM
   ```

2. **Create a Virtual Environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**:

   Create a `.env` file in the root directory and add your Groq API key:

   ```env
   GROQ_API_KEY=your_groq_api_key_here
   ```

## Running the Application

Start the Streamlit application using the following command:

```bash
streamlit run app.py
```

Replace `app.py` with the filename containing your Streamlit code.

## Usage

1. **Enter Your Groq API Key**: Use the sidebar to securely input your Groq API key.
2. **Start Chatting**: Type your queries into the chat input. The chatbot will process your question, search the web using the integrated tools, and provide a comprehensive answer.
3. **View Streaming Responses**: Watch as the chatbot's thought process and actions are displayed in real-time, providing transparency into how answers are derived.

## Technologies Used

- [Streamlit](https://streamlit.io/): For building the interactive web interface.
- [LangChain](https://www.langchain.com/): Framework for developing applications powered by language models.
- [Groq](https://groq.com/): Provider of high-performance LLMs.
- [Arxiv API](https://arxiv.org/help/api/index): For accessing scientific papers.
- [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page): For retrieving Wikipedia content.
- [DuckDuckGo Search API](https://duckduckgo.com/api): For performing web searches.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by examples from [LangChain's Streamlit Agent](https://github.com/langchain-ai/streamlit-agent).
- Utilizes the `StreamlitCallbackHandler` for real-time feedback during agent execution.

## Contact

For questions or feedback, please contact [your.email@example.com](mailto:your.email@example.com).
