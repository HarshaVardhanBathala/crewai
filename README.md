AI in February: 28 Days of Generative AI
Day 23: Creating a Multi-Agent System Using CrewAI – File Structure & Setup
Yesterday, we discussed how CrewAI enables multiple AI agents to work together to complete complex tasks. Today, let’s dive into the file structure and setup process so you can build your own CrewAI-powered multi-agent system!
📌 GitHub Repository: https://github.com/HarshaVardhanBathala/crewai

File Structure for CrewAI
CrewAI organizes AI agents and tasks using YAML configuration files to define roles and responsibilities. Below is the standard file structure for a multi-agent CrewAI project:
Important file
project_file/
│── config/
│ ├── agents.yaml  # Define agent roles, names, and behaviors
│ ├── tasks.yaml  # Assign tasks and define execution order
│── main.py      # Initializes CrewAI agents and executes tasks
│── requirements.txt # Required dependencies
│── README.md     # Documentation for the project

Making changes to this:
1) Defining Agents in config/agents.yaml

The agents.yaml file is where we define the AI agents, their names, roles, and capabilities. Each agent is designed for a specific purpose within the system.

2) Assigning Tasks in config/tasks.yaml
This file outlines what each agent will do and how they interact with each other. You can specify execution order and dependencies.

3) Running Agents & Tasks in main.py
Now that we’ve defined agents and tasks, we need to load them and execute the system in main.py.

Steps to Set Up and Run CrewAI
1) Install CrewAI CLI -   !pip install crewai
2) Create a New CrewAI Project - crewai create crew latest-ai-development 
3) Move to folder -  cd latest-ai-development
4) Install Dependencies - crewai install
5) Select Your LLM Model:
CrewAI supports multiple LLM models. If you are using:
🔹Ollama (Local LLM) → Make sure it’s installed and running.
🔹 OpenAI API → Set your OPENAI_API_KEY before running the script.
6) Run the Multi-Agent System - python main.py

Feel free to explore and experiment with CrewAI by assigning different roles to agents and creating new use cases. Customize tasks, adjust workflows, and see how AI agents can collaborate to solve various challenges efficiently!

The images below showcase how CrewAI agents collaborate in a sequential workflow. Each agent generates a response based on its assigned role, and subsequent agents utilize this information to refine and enhance the output. This process ensures structured, context-aware, and high-quality responses, demonstrating the power of multi-agent collaborationin AI.

#CrewAI #AIAgents #MultiAgentSystems #AIWorkflow #ArtificialIntelligence #Automation #MachineLearning #LLMs #AIInnovation #FutureOfAI #TechTrends #AIForBusiness #AIApplications #GenerativeAI
