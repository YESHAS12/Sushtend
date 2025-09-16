# Sushtend
# Groq Call Transcript Analyzer

This is a simple FastAPI app that:
- Accepts a customer call transcript (via web form).
- Uses Groq API to summarize and extract sentiment.
- Prints results on the web page.
- Saves results to `call_analysis.csv` and  `call_analysis.xlsx`.

## Setup

1. Clone or unzip this project.
2. Create virtual environment and install requirements:

```bash
python -m venv venv
source venv/bin/activate   
pip install -r requirements.txt
```

3. Set your Groq API key:

setx GROQ_API_KEY "sk-..."    
```

4. Run the server:

```bash
uvicorn main:app --reload
```

5. Open browser at http://127.0.0.1:8000

## Files
- `main.py`: FastAPI app
- `requirements.txt`: Python dependencies
- `call_analysis.csv`: file according to the guidelines
- `call_analysis.xlsx`: file according to the guidelines
