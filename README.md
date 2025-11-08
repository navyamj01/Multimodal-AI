# Multimodal-AI

Visual Question Answering App (Gradio + ViLT)

This project is a simple yet powerful Visual Question Answering (VQA) web app built using Gradio and the ViLT (Vision-and-Language Transformer) model. You can upload an image, ask any question about it, and the AI will try to answer using multimodal understanding.

# Features

1. Upload any image and ask a question about it

2. Uses dandelin/vilt-b32-finetuned-vqa, a transformer trained for VQA

3. Clean Gradio interface

4. Runs locally or can be deployed to platforms like Render, Hugging Face Spaces

# Installation

Clone this repository:

git clone https://github.com/yourusername/yourrepo.git
cd yourrepo

# Install dependencies:

pip install torch gradio transformers Pillow

# How It Works

The ViLTProcessor prepares the image and question for the model.

The ViLTForQuestionAnswering model predicts the most likely answer.

Gradio builds an easy-to-use interface around your model.

# Run the App

Start the app locally:

python app.py


Gradio will give you a URL like:

Running on http://127.0.0.1:7860

Open it in your browser and try it out!

# Project Structure
📂 project-folder
 └── app.py           # Main application file
 └── README.md        # Project documentation
