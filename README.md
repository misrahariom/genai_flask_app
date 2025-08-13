# GenAI Flask App

This repository contains a basic implementation of Generative AI features in Python.

The project includes **two independent Python apps**:

---

## 1. `capital.py`
A standalone script that fetches the **capital of Canada** using various Large Language Models (LLMs).

### Steps to Run
1. Install dependencies:
   ```bash
   pip install ibm-watsonx-ai
2. Add your IBM WatsonX API key inside capital.py.
3. Execute the script:
   ```bash
   py capital.py

## 2. LangChain-based Flask App
A LangChain-based application that queries LLaMA, Granite, and Mixtral models to:
Get the capital of Canada and Provide a fun fact about it

### Steps to Run
  1. Install dependencies:
     ```bash
     pip install Flask langchain-ibm langchain
  2. Run the LLM test script:
     ```bash
     py llm_test.py
  3. Start the Flask app:
      ```bash
      py app.py

## Project Structure
    
      genai_flask_app/
      │
      ├── capital.py           # Standalone LLM-based capital finder
      ├── model.py             # Langchain LLM model to initialize and prompts file
      ├── config.py            # config file to store credentials and model Ids
      ├── llm_test.py          # LangChain LLM test script
      ├── app.py               # Flask app serving LLM responses
      ├── template/index.html  # index.html file for Flask app
      └── README.md            # Project documentation


## Requirements
Python 3.9+
IBM WatsonX API Key

## Notes
Ensure you have a valid IBM WatsonX API key before running any scripts.

Both apps run independently.

## License
This project is for educational/demo purposes.
Feel free to modify and extend it.
