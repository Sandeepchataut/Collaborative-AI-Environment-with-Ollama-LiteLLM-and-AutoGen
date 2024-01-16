# Collaborative-AI-Environment-with-Ollama-LiteLLM-and-AutoGen
This repository contains a Python script that demonstrates a cutting-edge implementation of a collaborative AI environment. It integrates Ollama, LiteLLM, and AutoGen to create a dynamic, multi-agent system capable of handling complex tasks and interactions in a simulated group chat setting. 
# Features
Ollama Integration: Sets up a local server to run large language models like Llama 2, optimizing the use of model weights and configurations.
LiteLLM Proxy: Middleware for standardized API calls to various language model services, simplifying the interaction with multiple AI models.
AutoGen Framework: Utilizes a multi-agent conversation framework to create diverse AI agents, each performing unique roles within a simulated group chat environment.
# Installation
curl https://ollama.ai/install.sh | sh

pip install litellm[proxy]

pip install pyautogen

