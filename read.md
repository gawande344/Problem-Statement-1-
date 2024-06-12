# Sales Conversation Dataset Generation

## Description
This project generates a sales conversation dataset inspired by the research paper "Let the LLMs Talk". The dataset is generated using the OpenAI GPT-3 model, focusing on creating coherent and contextually appropriate sales dialogues.

## Requirements
- Python 3
- OpenAI API key
- `openai` Python library

## Installation
1. Install the OpenAI Python library:
    ```bash
    pip install openai
    ```
2. Set your OpenAI API key in the `run.py` script:
    ```python
    openai.api_key = 'YOUR_OPENAI_API_KEY'
    ```

## Usage
1. Run the script to generate the dataset:
    ```bash
    python run.py
    ```

## Output
The script will generate a `sales_conversations.csv` file with the following columns:
- Salesman
- User
- Timestamp

Each response in the conversation comprises 50-75 words.

## Evaluation Metrics
The generated dataset is evaluated based on:
- Contextual relevance and understanding
- Coherence, fluency, and readability
- Creativity and engagement
- Toxicity and bias mitigation
- Number of products sold
- Accuracy and completeness of information
- Compute time to generate data

## Bonus
For every additional 10 sets of dialogues, bonus points are awarded.
