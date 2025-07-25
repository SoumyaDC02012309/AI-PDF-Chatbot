# README: Setting Up Your Environment with Pip and Anaconda

## Prerequisite: Install Anaconda Prompt and Pip
Follow the official installation guides to set up Anaconda Prompt and Pip on your system:  
- [Install Anaconda Prompt Documentation](https://www.anaconda.com/docs/getting-started/anaconda/install)
- [Install Pip Documentation](https://pip.pypa.io/en/stable/installation/)
---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Anaconda and Pip are already installed):

```bash
conda create -n ai_pdf_chatbot python=3.12
conda install langchain langchain_community langchain_huggingface faiss-cpu pypdf
conda install huggingface_hub
pip install streamlit

```
Or You Can Run the following command

```bash
conda create -n ai_pdf_chatbot python=3.12
conda install -r requirements.txt
```

## Use of .env file

- Get your **GROQ API KEY** and **Huggingface Token** from the respective websites after logging in to the website 
- Add the **GROQ API KEY** and **Huggingface Token** in the .env file

## Data

Make a folder inside this main folder and name that **data**. Inside that put your pdfs of your choice that you want to feed the chatbot


