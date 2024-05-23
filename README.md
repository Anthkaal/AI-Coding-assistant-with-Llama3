# AI-Coding-assistant-with-Llama3

Let's build an AI Coding assistant with Llama3  

Step 1. Download llama3 with Ollama 🦙

Ollama is an open-source tool to run Large Language Models locally, that you can download for free from here.
ollama.com

You can now download llama3 (8B parameters), from the command line
$ ollama pull llama3

Step 2. Add a System Message to llama3 to act as a Python coding assistant

Pass a system message to Llama3, to steer the model towards your goal.

You can achieve this will Ollama in 2 steps:

1. Create a Modelfile with your adjustments
2. $ ollama create my-python-assistant -f ./Modelfile

If you now list your models you will find your newly created my-python-assistant
