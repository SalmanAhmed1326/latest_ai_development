# LatestAiDevelopment Crew

Welcome to the LatestAiDevelopment Crew project, powered by [crewAI](https://crewai.com). This template is designed to help you set up a multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

## Installation

Ensure you have Python >=3.10 <=3.13 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` into the `.env` file**

- Modify `src/latest_ai_development/config/agents.yaml` to define your agents
- Modify `src/latest_ai_development/config/tasks.yaml` to define your tasks
- Modify `src/latest_ai_development/crew.py` to add your own logic, tools and specific args
- Modify `src/latest_ai_development/main.py` to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```
**.
├── tools/config/
│   ├── agents.yaml       # Configuration for agents
│   ├── tasks.yaml        # Configuration for tasks
├── latest_ai_development/
│   ├── crew.py           # Crew definition, including agents and tasks
    ├── main.py               # Entry point for running, training, and testing
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
**

This command initializes the latest-ai-development Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a `report.md` file with the output of a research on LLMs in the root folder.

## Understanding Your Crew

The latest-ai-development Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.



Let's create wonders together with the power and simplicity of crewAI.
