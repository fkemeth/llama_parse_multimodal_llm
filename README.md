# Llama Parse Multimodal LLM

This repository contains code for using a multimodal LLM with LlamaParse to answer questions about documents.

## Overview

The project is organized as follows:

- `run_example1_multimodal.ipynb`: Code to run the Llama Parse and the multimodal LLM on Example 1
- `run_example2_multimodal.ipynb`: Code to run the Llama Parse and the multimodal LLM on Example 2
- `requirements.txt`: List of Python dependencies
- `data/`: Directory containing sample documents and images for testing

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/llama-parse-multimodal-llm.git
   cd llama-parse-multimodal-llm
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set up your LlamaParse API key:
   - Create a `.env` file in the project root
   - Add your API key: `LLAMA_PARSE_API_KEY=your_api_key_here`

5. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your API key: `OPENAI_API_KEY=your_api_key_here`


