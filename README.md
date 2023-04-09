# chatPDF

<img src="screenshot.png" width="800">

Chat with any PDF using GPT3.5-turbo, faiss vector database and InstructorEmbedding. 

## Installation

Tested on Ubuntu 22.04

- Create a new conda env `conda create -n chatpdf python-3.9`
- Activate the conda env `conda activate chatpdf`
- Install required packages `pip install -r requirements.txt`
- Install faiss vector database `conda install -c conda-forge faiss-gpu`

## Launch the gradio interface

`python chat.py`

## Acknowledgements

This code is based on two similar projects
- https://github.com/mayooear/gpt4-pdf-chatbot-langchain
- https://github.com/amrrs/LLM-QA-Bot
