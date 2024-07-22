# machine-translation-transformer-model

English to Punjabi Machine Translation Transformer Model
Overview
This repository contains resources for an English-to-Punjabi machine translation model. The model leverages the ai4bharat/IndicNER tokenizer for Punjabi sentences and the bert-base-uncased tokenizer for English sentences, built using TensorFlow and Hugging Face's Transformers library.

Table of Contents
Installation
Dataset
Training

Clone the repository:

bash
Copy code
git clone https://github.com/garvkhurana/machine-translation-transformer-model.git
cd english-punjabi-translation
Set up a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
Install the required packages:

Install the dependencies listed in the requirements.txt file using:

bash
Copy code
pip install -r requirements.txt
Dataset
The dataset used for training this model consists of 155,000 English sentences with corresponding Punjabi translations. You can find the dataset here.

Data Format
Ensure the dataset is in the following format:

English Sentence	Punjabi Sentence
Hello	ਸਤ ਸ੍ਰੀ ਅਕਾਲ
How are you?	ਤੁਸੀਂ ਕਿਵੇਂ ਹੋ?
...	...
Training
The model uses the tokenizer:
Helsinki-NLP/opus-mt-pa-en

Ensure to split the dataset into training and testing sets appropriately, maintaining a good balance between the two for effective training and evaluation.


Acknowledgments
Tokenizers: Helsinki-NLP/opus-mt-pa-en 
Frameworks:Pytorch and Hugging Face's Transformers library for providing the necessary tools to build and train the model.
Dataset Providers: The sources of the English-Punjabi translation data.
