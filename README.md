# Fine-tuning a Model for Anglicization of Polish Names and Toponyms

## Introduction
You have a Facebook penfriend from Poland. His name is Alexandre, but it's  written as Aleksandre in Poland. Recently, he traveled abroad and posted a photo with Stany Zjednoczone (the United States) as the geolocation. You can't understand where he is since the geolocation is in Polish. This frustrates you, so you decide to fine-tune a transformers model so that all Polish names and toponyms are automatically anglicized.
---
## Learning Outcomes
In this project, you will learn how to fine-tune a T5 model to convert Polish names and locations into their English (anglicized) equivalents. You will gain practical skills in corpus creation, setting specific parameters for fine-tuning, monitoring the training process, and evaluating fine-tuning results.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](./anglicization.ipynb)
---

## Project Structure
```
├── data/# Directory containing the dataset for fine-tuning
│   ├── polish_names.csv # CSV file with Polish names and their English equivalents
│   └── toponyms_of_poland.csv # CSV file with Polish toponyms and their English equivalents
├── anglicization.ipynb # Jupyter notebook for fine-tuning the T5
├── .gitignore # ignored files in version control
├── README.md # Project documentation
└── requirements.txt #required Python packages
```
---



