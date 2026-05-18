# Enterprise RAG System

A simple Enterprise RAG (Retrieval-Augmented Generation) System built using Python, Streamlit, AWS Bedrock, Amazon S3, and Boto3.

## Features

- Upload PDF, DOCX, and TXT files
- Store documents in Amazon S3
- Ask questions using AI
- AI gives answers with document references
- Simple Streamlit interface

## Tech Stack

- Python
- Streamlit
- AWS Bedrock
- Amazon S3
- Boto3

## Project Structure

enterprise-rag-system/
│── app.py  
│── bedrock_rag.py  
│── config.py  
│── requirements.txt  
│── documents/  

## Installation

git clone <repo-url>

cd enterprise-rag-system

python -m venv myenv

myenv\Scripts\activate

pip install -r requirements.txt

## AWS Configuration

Create a `.env` file and add:

AWS_ACCESS_KEY_ID=your_key

AWS_SECRET_ACCESS_KEY=your_secret

AWS_DEFAULT_REGION=us-east-1

## Run Project

streamlit run app.py

## Example Questions

- What is the leave policy?
- What are office timings?
- Explain security rules.

## Author

Devendra Gangurde

## License

Educational and portfolio project.