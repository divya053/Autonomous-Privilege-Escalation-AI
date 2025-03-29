# Autonomous-Privilege-Escalation-AI

To use its capabilities, you'll need an OpenAI API key. Follow these steps to obtain and configure your key:

Obtaining an OpenAI API Key
Create an Account: Visit OpenAI and sign up for an account if you don't already have one.
Apply for API Access: Navigate to the API section and apply for access. You might need to provide details about your intended use case.
Get Your API Key: Once approved, you will receive an API key.
Configuring the API Key in Your Environment
Create the .env File
Add Your API Key: Open the .env file and add the following line:
OPENAI_API_KEY=your_api_key_here
Replace your_api_key_here with the API key you obtained from OpenAI.

#Run with Docker
Before running the project, ensure you have installed:
Docker
Docker Compose
OpenAI key

#Setup
Clone the repository and launch the Docker containers:
docker compose up -d
Access the application at: https://127.0.0.1:5000

#Run Locally
Ensure the following are installed:
Python 3 and pip
OpenAI key

#Setup
Clone the repository and prepare the environment
./generate_certs.sh
pip install -r requirements.txt
python app.py
Access the application at: https://127.0.0.1:5000

#Integrated Tools
Integrates several tools for privilege escalation enumeration, including:
BeRoot: A tool for identifying common privilege escalation vectors in Windows environments.
LinPEAS: A script that audits Linux environments for potential misconfigurations and vulnerabilities.

#Features
Import and export instructions
For example, to capture a flag

Use external tools for enumerations
For example, executing BeRoot and feeding the results to the AI
