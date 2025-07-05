# CalmPal_Mental-Health-Chatbot

## Empowering Mental Well-being with AI-Powered Conversations

## Overview:

CalmPal is an AI-powered mental health chatbot designed to provide empathetic, supportive, and contextually relevant conversations to users experiencing mental distress. Using Google Gemini AI and NLP techniques, CalmPal offers users a safe space to share their emotions and receive helpful responses.

🔹 Live Demo: CalmPal Chatbot                                                                                                                                                                
🔹 Tech Stack: Python | Streamlit | Google Gemini API | Scikit-learn | NLTK |

## Features:
✅ AI-Powered Conversations – Provides empathetic, mental health-friendly responses using Google Gemini API.                                                                                   
✅ Real-time Chatbot – Fast and interactive chatbot with NLP capabilities.                                                                                                                     
✅ Emotionally Supportive Responses – Trained to detect emotions and offer relevant support.                                                                                                   
✅ Deployed on Streamlit Cloud – Accessible from anywhere, no local installation required.                                                                                                     
✅ Scalable & Customizable – Can be integrated into apps, websites, or AI assistants.

## Getting Started:

**1️⃣ Clone the Repository:**

git clone https://github.com/yourusername/CalmPal-Chatbot.git                                                                                                                                
cd CalmPal-Chatbot

**2️⃣ Set Up a Virtual Environment (Optional but Recommended)**

python -m venv env                                                                                                                                                                           
source env/bin/activate  # On macOS/Linux                                                                                                                                                    
env\Scripts\activate  # On Windows                                                                                                                                                           

**3️⃣ Install Dependencies**                                                                                                                                                                  
pip install -r requirements.txt

**4️⃣ Set Up Google Gemini API**
* Get API Key:
* Sign in to Google AI Studio.
* Click on Get API Key and copy it.
* Store API Key in Environment Variables:
export GOOGLE_API_KEY="your_google_api_key"                                                                                                                                                  
(Windows users can set it in .env file or manually inside app.py).

## Running the Chatbot Locally
🔹 Using Streamlit                                                                                                                                                                           

streamlit run app.py                                                                                                                                                                         
Once the server starts, open the local URL (e.g., http://localhost:8501) to interact with the chatbot.

## Project Structure

CalmPal-Chatbot/                                                                                                                                                                             
│── app.py                # Main Streamlit chatbot app
│── requirements.txt      # Dependencies                                                                                                                                                     
│── README.md             # Project documentation                                                                                                                                            
│── background.jpg        # Background image for Streamlit UI                                                                                                                                
│── logo.jpg              # CalmPal logo                                                                                                                                                                                                                                                                                        
│── .env                  # Environment variables (Google API key)

## Deploying on Streamlit Cloud
* Push your project to GitHub.
* Go to Streamlit Cloud.
* Create a new app → Select GitHub repo → Set app.py as the main script.
* Deploy! Your chatbot will now be accessible online.

## Future Enhancements
* Sentiment Analysis – Improve chatbot adaptability to emotional tones.
* Voice-based Interaction – Enable users to talk to the chatbot.
* Multi-Language Support – Expand chatbot support for different languages.
* Memory-based Conversations – Maintain chat history for better context retention.

## Contributing

Welcome contributions! To contribute:
1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes and create a pull request.

## Deployed Project link:
https://calmpal-chatbot-for-mentalhealth.streamlit.app/
