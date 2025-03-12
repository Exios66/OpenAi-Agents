# OpenAI API Project

This project uses the OpenAI API to generate content.

## Setup

1. Install the required packages:
   ```
   pip install openai python-dotenv
   ```

2. Create a `.env` file in the root directory with your OpenAI API key:
   ```
   OPENAI_API_KEY=<YOUR_OPENAI_API_KEY_HERE>
   ```

3. To load the environment variables, update your code to use python-dotenv:
   ```python
   from dotenv import load_dotenv
   load_dotenv()  # This loads the variables from .env
   ```

## Security

- Never commit your API keys to version control
- The `.env` file is included in `.gitignore` to prevent accidental commits
- Always use environment variables for sensitive information
 
