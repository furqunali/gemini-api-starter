# ✨ Gemini API Starter

A minimal Python client for **Google's Gemini** generative-AI API — configure a key, pick a model, and get a completion. A clean starting point for building on top of Gemini.

## Features

- Loads the API key securely from a `.env` file (`python-dotenv`)
- Uses the `google-generativeai` SDK with `gemini-1.5-flash`
- Sends a prompt and prints the model's response

## Setup

```bash
pip install google-generativeai python-dotenv
echo "API_KEY=your_key_here" > .env
python gemini_project.py
```

---

*Part of [Furqan Ali](https://github.com/furqunali)'s portfolio — AI & Intelligent Automation / Digital Transformation.*
