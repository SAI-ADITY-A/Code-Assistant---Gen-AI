# Code Assistant - Ollama + Langchain + Streamlit

This project demonstrates how to create a personal code assistant using a local open-source large language model (LLM). We utilize Codellama, a fine-tuned version of Llama specifically developed for coding tasks, along with Ollama, Langchain, and Streamlit to build a robust, interactive, and user-friendly interface.

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
  - [Environment](#environment)
  - [Installing Dependencies](#installing-dependencies)
- [Customizing and Testing the Model](#customizing-and-testing-the-model)
- [Building and Running the Application](#building-and-running-the-application)
- [References](#references)

---

## Overview
The goal of this project is to build a code assistant powered by an open-source LLM fine-tuned for coding tasks. This assistant, called **CodyBot**, can:
- Understand and generate code in multiple programming languages.
- Troubleshoot coding issues.
- Optimize algorithms.
- Explain complex programming concepts clearly.

## Prerequisites
Ensure the following software is installed before starting:
- **[Ollama](https://ollama.com/)**: To facilitate working with LLMs on a local setup.
- Familiarity with the **OpenAI API** and **Langchain integration** for quicker development.

## Setup

### Environment
1. **Create a new virtual environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

2. **Run the App**
   ```
   streamlit run app.py
   ```
