
# Installation

Welcome to `genai-agentos`! We're excited to have you here. Let's get the necessary tools installed so you can start building. 

The best way to install the `genai-agentos` package is through `pip`, Python's package installer.

## Prerequisites

* **Python 3.9+**
* An **OpenAI API Key** (for the default examples)

## Install with Pip

We strongly recommend creating a **virtual environment**. This is a great habit to get into as a developer, as it keeps your project dependencies isolated and prevents conflicts.

```bash
# First, create a new directory for your project and navigate into it
mkdir my-first-agent
cd my-first-agent

# Next, create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Now, install the core package using pip
pip install genai-agentos
```

And that's it! You now have the core genai-agentos library installed and are ready to go.

### Optional Dependencies


The agent protocol is designed to be model-agnostic. We include a few "extra" installation options for common Large Language Models (LLMs) to make your life easier.

OpenAI
To use OpenAI models like GPT-4, install the openai extra:

```
pip install "genai-agentos[openai]"

```


Now that you're all set up, let's move on to the Quick Start and build something!