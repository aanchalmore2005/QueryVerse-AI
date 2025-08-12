# QueryVerse-AI

A College Enquiry AI Chatbot built with Flask, Firebase, and LLaMA 3 integration, designed to handle student queries, provide information, and streamline the enquiry process.

# Features
- AI Chatbot powered by LLaMA 3 for natural conversation
- Flask Backend for smooth request handling
- Firebase Integration for authentication & database storage
- OCR Support for reading text from images
- File Uploads to process and answer document-based queries
- Chat History to keep track of past conversations
- Dark Mode UI for a modern look

# Project Structure
**QueryVerse-AI/**
│── app.py # Main Flask application
│── requirements.txt # Python dependencies
│── static/ # CSS, JS, and images
│── templates/ # HTML templates
│── firebase-credentials.json (ignored in repo)

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/QueryVerse-AI.git
   cd QueryVerse-AI
   ```
   
2. Create a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application
   ```bash
   python merged_app.py
   ```

   Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.


