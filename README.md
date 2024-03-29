# SecureBERT-NER Implementation

This repository contains an implementation of the SecureBERT-NER model from the CyberPeace Institute. The model is used to extract named entities from security advisory texts.

## Description

The SecureBERT-NER model is a Named Entity Recognition (NER) model specifically trained for cybersecurity texts. It can identify various entities such as identities, security teams, tools, times, and attacks.

![image](https://github.com/PriyankaMohan94/cybersecurity-ner/assets/158774209/0cbc3e15-2c19-4fd3-a7f5-5d95490d4af1)


## Installation

To use this code, you need to have the `transformers` library installed. You can install it using pip:

```bash
pip install transformers
```


## Usage

Here’s a basic example of how to use the code:

```bash
from transformers import pipeline

# Initialize the pipeline with the pre-trained model
nlp = pipeline('ner', model='CyberPeace-Institute/SecureBERT-NER')

# Use the pipeline to extract entities from the text
entities = nlp(text)
```

For more detailed usage, please refer to the example provided in the repository.

## Reference 

HuggingFace - https://huggingface.co/CyberPeace-Institute/SecureBERT-NER
