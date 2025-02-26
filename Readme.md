# 🏥 AI_Doctor

AI_Doctor is an AI-powered medical diagnostic assistant that utilizes multimodal Large Language Models (LLMs) to analyze images and provide medical insights based on user queries. This project leverages the **GROQ API** to process and interpret images, enabling users to receive preliminary diagnoses for skin conditions.

## 🚀 Features

- 📸 **Image-based diagnosis** – Upload an image and get AI-powered analysis.
- 🎙 **Voice-based interaction** – Convert speech to text and vice versa.
- 🤖 **GROQ Multimodal LLM Integration** – Uses the **llama-3.2-90b-vision-preview** model.
- 📝 **Text-based queries** – Users can describe their symptoms for better insights.
- 🔗 **Real-time AI responses** – Quick and efficient results.
- 🌐 **Gradio-based UI** – Interactive web application for easy access.

## 🏗 Project Structure
AI_Doctor/
│── .env                     # API keys 
│── brain_of_the_doctor.py    # Core script for image processing and AI analysis
│── voice_of_the_doctor.py    # Converts AI responses to speech (text-to-speech)
│── voice_of_the_patient.py   # Converts patient’s voice input to text (speech-to-text)
│── gradio_app.py             # Web-based UI using Gradio
│── README.md                 # Project documentation
│── requirements.txt          # Python dependencies


##  1. Installation & Setup 🔧

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/AI_Doctor.git
cd AI_Doctor

## 2.Create a Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate     # For Windows
