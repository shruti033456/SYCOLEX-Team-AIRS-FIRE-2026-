# SYCOLEX-Team-AIRS-FIRE-2026
This repository contains the source code and experimental implementation for the SYCOLEX study on detecting sycophantic behavior in large language models using legal case judgments.

## Overview
The project investigates whether language models exhibit sycophantic behavior when responding to oppositely framed prompts concerning legal case outcomes. The experimental pipeline includes data preprocessing, response analysis, representation learning, classifier training, and evaluation.

## Repository Contents

* `SYCOLEX_TASK2.ipynb` — Main notebook containing the experimental implementation.
* `README.md` — Project description and reproducibility instructions.

## Running the Experiments
* Clone or download this repository.
* Install the required Python packages: pip install -r requirements.txt
* Open SYCOLEX_TASK2.ipynb and configure the dataset path according to the instructions in the notebook.


## Model
The classification component uses the pretrained DeBERTa-v3-small transformer model:
https://huggingface.co/microsoft/deberta-v3-small


