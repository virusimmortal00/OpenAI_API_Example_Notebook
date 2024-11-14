# First create a new Python virtual environment

python3 -m venv venv

# Then activate the virtual environment

source venv/bin/activate

# Then install the required packages

pip install -r requirements.txt

# Then create a .env file and add your OpenAI API key

touch .env
echo "OPENAI_API_KEY=<your_api_key>" >> .env
