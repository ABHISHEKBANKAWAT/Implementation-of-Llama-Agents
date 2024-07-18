# Implementation-of-Llama-Agents
llama-agents is an async-first framework for building, iterating, and productionizing multi-agent systems, including multi-agent communication, distributed tool execution, human-in-the-loop, and more!
If you want to know more **You can read more about this in my [Article]([https://www.analyticsvidhya.com/blog/2024/07/llama-agents-agents-as-a-service/?utm_source=social%20&utm_medium=github])

## Basic Implementation of Llama Agents
The flow of Implementation will be like this -
1. Create Tool
2. Create Agent
3. Create Components
4. Llama kickoff

The quickest way to get started is by using an existing agent (or agents) and integrating them into a launcher.
Below is a simple example using two agents from llama-index.
First, let's set up the agents and initial components for our llama-agents system:

Setting OPEN_API_KEY in WINDOWS - 
Set OPENAI_API_KEY = ”sk-XXXXXXX”

For Linux and macOS - 
export OPENAI_API_KEY="sk-XXXXX"
