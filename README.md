# Image-Caption-Generator-using-CNN-RNN
This project builds an Image Caption Generator that automatically generates natural language descriptions for images. It uses a pre-trained CNN (VGG16) for feature extraction and an LSTM-based RNN for caption generation. The Flickr8k dataset is used for training.

Problem Statement:
Generate accurate and human-like captions for images using deep learning techniques.

Approach:

Extract image features using VGG16

Preprocess and tokenize captions

Train an LSTM decoder model

Use greedy or beam search for inference

Technologies Used:

Python, TensorFlow, Keras

NumPy, Pandas, Matplotlib

NLTK for BLEU score calculation

Dataset:

Flickr8k dataset (8,000 images, each with 5 captions)

Images resized to 224x224

Captions cleaned and tokenized with start and end tokens

Evaluation Metrics:

BLEU Score

METEOR

CIDEr

Deliverables:

Jupyter notebooks

Trained model and tokenizer

Feature extraction and caption generation code

Cleaned and preprocessed data

Use Cases:

Captioning for websites and image galleries

Assisting visually impaired users

Automated alt-text generation
