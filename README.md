# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Anaconda Prompt and Pip
Follow the official installation guides to set up Anaconda Prompt and Pip on your system:  
[Install Anaconda Prompt Documentation]([https://www.anaconda.com/docs/getting-started/anaconda/install])
[Install Pip Documentation]([https://pip.pypa.io/en/stable/installation/])
---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
conda create -n medical_ai_chatbot python=3.12
conda install langchain langchain_community langchain_huggingface faiss-cpu pypdf
conda install huggingface_hub
pip install streamlit



