
Table of Contents
About Serenity AI
Features
Installation
Usage
Technologies Used
Project Structure
Contributing
License


**About Serenity AI**
Serenity AI is an interactive, voice-controlled mental health assistant designed to engage users in real-time conversations, provide compassionate responses, and support mental well-being. This application utilizes Google Cloud’s Speech-to-Text and Text-to-Speech services to recognize and respond to spoken queries, and it leverages the Gemini AI model for generating conversational responses.

**Features**
Voice Recognition: Converts spoken input into text using Google Cloud Speech-to-Text.
AI-Driven Conversations: Generates intelligent, empathetic responses through Gemini AI.
Text-to-Speech Responses: Converts AI responses back to speech, creating a natural conversational flow.
Real-Time Interaction: Supports real-time conversation, allowing continuous, hands-free interaction.


**Installation**
Clone the Repository:
git clone https://github.com/Devanshi098/serenityAI.git
cd serenity-ai

Install Dependencies: Make sure you have Python 3.7+ installed, then install required packages:

pip install -r requirements.txt
Set Up API Keys:

Obtain API keys for any necessary services (e.g., natural language processing, emotion recognition).
Add them to a .env file in the root directory:
makefile
API_KEY=your_api_key_here
Run the Application:
python main.py
Usage
Chat with Serenity AI: Open the application and begin a conversation by typing or using voice commands.
Track Moods: Update your mood status daily to observe trends.
View Recommendations: Access personalized suggestions based on recent interactions.

**Technologies Used**
Python: Primary programming language
Google Cloud Speech-to-Text: For voice recognition
Google Cloud Text-to-Speech: To synthesize responses as spoken audio
Generative AI (Gemini AI): Provides conversational responses
PyAudio: For audio input
Pygame: For audio playback

serenity-ai/
├── main.py                      # Main application script
├── key.json                     # Google Cloud Speech-to-Text credentials
├── keyTTS.json                  # Google Cloud Text-to-Speech credentials
├── requirements.txt             # Project dependencies
├── README.md                    # Project documentation
└── .env.example                 # Example environment file for API keys


Contributing
We welcome contributions to Serenity AI! Please follow these steps:

**Fork the repository.**
Create a new branch: git checkout -b feature-branch.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin feature-branch.
Submit a pull request.
