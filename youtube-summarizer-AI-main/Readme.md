# YouTube Summarizer AI

A simple AI application that converts YouTube videos into articles and downloadable PDFs using Python, Streamlit, and Groq LLaMA models.

## Features

- Extract transcript from YouTube videos
- Generate AI-based articles
- Support multiple languages
- Download article as PDF
- Simple Streamlit interface
- Uses transcript fallback system

## Tech Stack

- Python
- Streamlit
- Groq LLaMA
- youtube-transcript-api
- yt-dlp
- ReportLab

## Project Structure

youtube-summarizer-ai/
│── app.py  
│── utils/  
│   ├── transcript.py  
│   ├── article_generator.py  
│   ├── pdf_generator.py  
│── .env  
│── requirements.txt  
│── README.md  

## Installation

git clone <repo-url>

cd youtube-summarizer-ai

python -m venv myenv

myenv\Scripts\activate

pip install -r requirements.txt

## Environment Variable

Create a `.env` file:

GROQ_API_KEY=your_api_key_here

## Run Project

streamlit run app.py

## How It Works

1. User enters YouTube URL
2. Transcript is extracted
3. AI generates article
4. PDF is created
5. User downloads the PDF

## Future Improvements

- DOCX export
- Cloud deployment
- Video preview
- Better analytics

## Author
Devendra Gangurde 

## License

Educational and portfolio project.
