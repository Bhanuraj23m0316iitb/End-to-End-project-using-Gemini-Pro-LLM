# Gemini AI Chatbot & Image Analysis Application

A Streamlit-based web application that demonstrates the capabilities of Google's Gemini AI models for both text-based conversations (Gemini Pro) and image analysis (Gemini Pro Vision).

## Features

- **Image Analysis**: Upload images and get AI-generated descriptions
- **Visual Q&A**: Ask specific questions about uploaded images
- **Conversational Chat**: Interactive chat interface with conversation history
- **Dual AI Integration**: Combines Gemini Pro (text) and Gemini Pro Vision (multimodal) models
- **Environment Security**: Secure API key management using .env files

## Prerequisites

- Python 3.7+
- Google API key (with access to Gemini AI)
- Google account with enabled Gemini API access

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd gemini-ai-app
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Create .env file:
```bash
GOOGLE_API_KEY=your_actual_api_key_here
```
## Usage
1. Start the application:
```bash
streamlit run app.py
```
2. Choose mode:
- **Image Analysis**: Upload an image and optionally add a prompt
- **Text Chat**: Type questions in the text input field

3. Interact with the AI:

