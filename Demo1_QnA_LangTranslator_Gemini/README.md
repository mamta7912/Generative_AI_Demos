Packages installed:
    
    python -m pip install --upgrade pip
    pip install --upgrade --quiet  langchain-google-genai pillow
    pip install streamlit
    pip install python-dotenv

Create and activate Virtual enviornment
    py -3.12 -m venv myvenv
    myvenv\Scripts\activate

Link to get a Google AI API key: 
    https://ai.google.dev/gemini-api/docs/api-key

Command to run QnA app:  
    streamlit run gemini_app_qa.py

Command to run language translator app:
    streamlit run gemini_applanguage_translator.py
