
Goal of this repo is to build a library of agents that individually can pick up sub tasks in the development process from story creation and refinement all the way to research, code generation, review and documentation. 
These agents can be run locally on machines with powerfull graphics cards (like apple silicon). 

## Setup

- Setup Ollama with a model like llama3.2
- Setup CrewAI
- Clone this project
- Run one of the agentSystems

## Stack
- [Ollama](https://github.com/ollama/ollama) (MIT license) 
- [CrewAi](https://github.com/crewAIInc/crewAI) (MIT license)
- [Weaviate](https://github.com/weaviate/weaviate) (BSD-3-Clause license) 
- Slack
- Jira

## Future project ideas

### Code base chat bot
Build a rag containing the code base to have a chatbot that we can ask questions about the code. 

### Open api spec creator
Build an agent that can create open api spec based on a story description. 

### Slack chat bot 
Build a set of agents that have access to all the knowledge about given slack channels and can answer similar questions that where already answered. 

### Story writer
Create stories directly in jira by listening to ongoing refinement discussions. 
