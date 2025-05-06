# scraper-llm

This script uses Selenium to interact with a webpage, log in using environment variables for email and password, navigate to a specific page, and extract relevant information from the page's HTML structure. It then uses a natural language processing library (langchain) to ask a conversational AI model (Ollama) to parse the extracted data according to a specified schema, resulting in a JSON-formatted output. The script repeats this process for different sections of the data and finally outputs the parsed data in a human-readable format.
