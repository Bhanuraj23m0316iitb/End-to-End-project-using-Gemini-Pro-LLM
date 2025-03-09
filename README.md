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
Install dependencies:

bash
Copy
pip install -r requirements.txt
Create .env file:

env
Copy
GOOGLE_API_KEY=your_actual_api_key_here
Usage
Start the application:

bash
Copy
streamlit run app.py
Choose mode:

Image Analysis: Upload an image and optionally add a prompt

Text Chat: Type questions in the text input field

Interact with the AI:

Get image descriptions

Ask follow-up questions about images

Maintain conversation context with chat history

Example Prompts
Image Mode:

"Describe this image in detail"

"What kind of plant is shown here?"

"Are there any safety concerns in this picture?"

Chat Mode:

"Explain quantum computing simply"

"What's the weather forecast philosophy?"

"Help me plan a healthy meal plan"

Configuration
Obtain Google API Key:

Visit Google AI Studio

Create API key for Gemini API

Application Settings:

Modify .env file with your API key

Adjust temperature/personality through model parameters

Technologies Used
Google Gemini AI: Core AI capabilities

Streamlit: Web application framework

Python: Backend logic

dotenv: Environment variable management

Pillow: Image processing

License
MIT License - see LICENSE file for details

Copy

This README provides:
- Clear installation/usage instructions
- Feature highlights
- Environment setup guidance
- Technology stack transparency
- License information
- Practical examples for user orientation

Adjust repository URLs and license details as needed for your specific implementation.
