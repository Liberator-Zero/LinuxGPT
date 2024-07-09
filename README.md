# LinuxGPT
Script that integrates ChatGPT into Linux CLI

#Steps to Ensure Correct Execution
#Save the Script:
#Ensure your script is saved as ask (or another preferred name).

#Make the Script Executable:
#Make the script executable by running:

chmod +x ask

#Move the Script to a Directory in PATH:
#Move the script to a directory that is in your PATH, such as /usr/local/bin:

sudo mv ask /usr/local/bin/

#Set the Environment Variable in a Secure File:
#Create a file to store your API key and set the appropriate permissions:

echo 'export OPENAI_API_KEY="your_openai_api_key_here"' > ~/.openai_key
chmod 600 ~/.openai_key

#Run the Script:
#Run the script with a question:

ask What is the capital of France?
