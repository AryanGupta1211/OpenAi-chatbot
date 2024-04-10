# Aryan's Chatbot

**Aryan's Chatbot** is a conversational interface application developed using **Streamlit** and **OpenAI**. This chatbot leverages the power of the GPT-3.5 model to generate responses based on user input, providing an interactive experience.

## Usage

### Prerequisites

- **Python 3.6 or higher**
- **Streamlit**
- **OpenAI Python library**

### Installation

1. Install Streamlit:

    ```
    pip install streamlit
    ```

2. Install the OpenAI Python library:

    ```
    pip install openai
    ```

### Configuration

Before running the application, initialize the OpenAI client with your API key:

```python
from openai import OpenAI

# Initialize the OpenAI client with your API key
client = OpenAI(api_key="your_openai_api_key_here")
