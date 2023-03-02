# Images_Data_Extraction
Image Classification for Yuliya Ph.D Candidate 


Introduction

This project aims to classify images based on their content, extract text from images, classify text into categories, and generate emotions associated with the text. It uses OpenAI's CLIP model for zero-shot image classification, EasyOCR for text extraction, langdetect for language detection, and GPT-3 for emotion generation.


Installation

Before running the script, ensure that the necessary libraries are installed by running the first cell in the notebook. The code checks the version of CUDA installed on the system and sets the PyTorch version suffix accordingly to ensure GPU acceleration. Finally, it installs PyTorch and other necessary libraries using the PyTorch stable download link and clip-by-openai library.

Functions

The notebook includes several functions for image classification, text extraction and translation, text classification, and emotion generation. Each function takes specific inputs and returns specific outputs.

Usage

To use the script, input the desired images into the "images" folder, set the necessary parameters in the "Set parameters" section, and run the final function "just_do_it". The output will be a CSV file in the "csv_result" folder that contains the image filename, image category probabilities, extracted text, text category probabilities, text category key words, and associated emotions.

Parameters

The "Set parameters" section includes variables for the categories, category words dictionary, and tokenize category detection. Modify these variables to fit the desired categories and words related to each category.

Credits
This project was developed by Alexis Vandriessche, Piero Rucci, Rafaella Porto and Pierre Warnier as part of Becode Ai Bootcamp. The code was developed using Python and various open-source libraries, including PyTorch, CLIP, EasyOCR, langdetect, spaCy, deep_translator, and OpenAI's GPT-3.
