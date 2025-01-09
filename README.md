# Ollama-Chatbot
# Enhanced Q&A Chatbot With OpenAI

This is a Streamlit app that uses LangChain and OpenAI models to create a Q&A chatbot. The chatbot is designed to answer user queries based on a variety of open-source models, including the **Ollama** model. It features an interactive interface to adjust parameters like **temperature** and **max tokens** for fine-tuning the model's responses.

## Features
- **Interactive Q&A Interface**: Ask questions directly to the chatbot and get responses.
- **Model Selection**: Choose from available open-source models like "mistral" for generating responses.
- **Parameter Tuning**: Adjust **temperature** and **max tokens** to control the creativity and length of the chatbot’s responses.
- **LangChain Integration**: The application integrates LangChain for chaining the prompt with the model for an enhanced experience.

## Installation

### Prerequisites
- Python 3.x
- Streamlit
- OpenAI API (for OpenAI models) or Ollama API (for open-source models)

### Install the dependencies:
To install the required dependencies, clone the repository and install the dependencies using pip.

```bash
pip install -r requirements.txt
```

### Run the application:
Once all dependencies are installed, you can run the Streamlit app with the following command:
```bash
streamlit run app.py
```
## Usage
1. Open the app: After running the app, open it in your browser at http://localhost:8501.
2. Model Selection: Select an open-source model (e.g., mistral) from the sidebar.
3. Adjust Parameters: Use the sliders to adjust the temperature (creativity of responses) and max tokens (response length).
4. Ask a Question: Type a question in the input box and click "Enter" or press "Submit" to get an answer from the chatbot.

## Project Structure
```bash
enhanced-qa-chatbot/
├── app.py                # Main Streamlit app
├── requirements.txt      # Required Python libraries
├── .env                  # Environment variables for API keys
└── README.md             # Project documentation
```

## Technologies Used
- Streamlit: For building the front-end user interface.
- LangChain: For chaining the prompt with the language model and processing.
- OpenAI & Ollama API: For using large language models to generate responses.
- dotenv: For loading environment variables from .env files.

## License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](./LICENSE) file for more details.
