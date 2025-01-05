# Pavelist Blog Generator

A Streamlit web application that generates blog posts using OpenAI's GPT-3.5 model.

## Features
- Generate blog posts with custom topics and keywords
- Adjust word count and language level
- Export to Word or PDF format
- Human-like writing option

## Setup
1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Add your OpenAI API key
5. Run the app:
   ```bash
   streamlit run blog-post-app.py
   ```

## Security Note
Make sure to keep your API key secure and never commit it to the repository. 