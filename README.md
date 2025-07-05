# Phishing Link Scanner

A web application that detects phishing URLs and scam file contents using machine learning and AI.

## Features
- URL Threat Detection (Phishing, Malware, Defacement, Benign)
- Scam link/Document Analysis (PDF/TXT)
- Gemini AI Integration
- Machine Learning Model based detection

## Usage
1. Install Python Libraries
- pip install flask google-generativeai PyPDF2
  
2. Set Up Google Gemini API Key
- Go to "Google AI Studio" and create an API key.
- Replace this line in main.py:
- os.environ["GOOGLE_API_KEY"] = "write your api key here" with:
- os.environ["GOOGLE_API_KEY"] = "your-real-api-key-here"

3. Run the Web App
- Make sure you're in the folder where main.py is saved, then run:
- Open cmd and run: python main.py

4. Open the Web App
- Go to your browser and open:
- http://127.0.0.1:5000/

You’ll see a cool dark-themed interface called ThreatGuard where you can:
- Upload PDF/TXT to detect scam content
- Enter a URL to check if it’s phishing/malware/etc.
