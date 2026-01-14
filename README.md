# Intelligent Multilingual Language Translation System


## Project Overview
This project implements an intelligent AI-driven multilingual language translation system.
The system automatically identifies the source language from user input, translates the text into a chosen target language, and produces voice output for the translated result.


## Problem Statement
Language differences create communication challenges across regions and cultures.
Manual translation methods are time-consuming and inefficient, making them unsuitable for real-time and large-scale applications.


## Objectives
- Automatically detect the source language from input text  
- Translate text into multiple target languages  
- Generate speech output for translated text  
- Provide a simple and user-friendly interface  


## Model Used
- facebook/nllb-200-distilled-600M  


## Technologies Used
- Python  
- PyTorch  
- Hugging Face Transformers  
- langdetect  
- gTTS (Google Text-to-Speech)  
- ipywidgets  
- Jupyter Notebook  


## Key Features
- Automatic language detection  
- Supports multiple Indian and international languages  
- High-quality neural machine translation  
- Text-to-speech voice generation  
- Interactive user interface using ipywidgets  


## How to Run the Project
1. Install required libraries:

    pip install -r requirements.txt

2. Open the notebook:

    jupyter notebook "language Translation System.ipynb"

3. Run all cells and start translating


## Project Structure
Language-Translation-System/
├── language_translation.ipynb
├── requirements.txt
├── README.md
└── output.mp3


## Ethical Considerations
- Translation results may not always be fully accurate  
- User input is not stored, ensuring privacy  

- Not suitable for legal, medical, or sensitive translations without human verification  
