# Document Assistant

LangGraph assistant for document Q&A, summarization, and calculations.

## Setup

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
```

Add your OpenAI API key to `.env`:

```
OPENAI_API_KEY=your_api_key_here
```

## Run

```bash
python main.py
```
