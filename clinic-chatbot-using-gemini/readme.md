# PharmaGen AI

PharmaGen AI is a simple AI chatbot made for pharmaceutical-related questions. It uses Google Gemini API and Streamlit to provide smart and context-aware responses.

## Main Features

- AI chatbot for pharma industry queries
- Memory-based conversation support
- Fast and interactive Streamlit UI
- Session chat history management
- Clear chat functionality
- Modular project structure

## Technologies Used

- Python
- Streamlit
- Google Gemini API

## Project Files

pharmagen-ai/
│── app.py  
│── chatbot/  
│   ├── gemini_client.py  
│   ├── memory_manager.py  
│   ├── prompt_builder.py  
│── .env  
│── requirements.txt  

## Installation

git clone <repo-url>

cd pharmagen-ai

python -m venv myenv

myenv\Scripts\activate

pip install -r requirements.txt

## Environment Setup

Create a `.env` file:

GEMINI_API_KEY=your_api_key_here

## Run the Project

streamlit run app.py

## How It Works

1. User asks a pharma-related question
2. Chat history is stored in memory
3. Prompt is generated
4. Gemini API gives response
5. Response is shown in chat UI

## Future Improvements

- Multi-language support
- Export chat feature
- Cloud deployment
- User authentication

## Author
Devendra Gangurde

## License

Educational and portfolio project.
