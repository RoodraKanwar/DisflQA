# DisflQA

This repository contains a fine-tuned T5-small model for the Question Rewrite task. Below are the key components:

1. T5_small.ipynb: This notebook contains the complete code for fine-tuning the T5-small model. The model has been fine-tuned on the dataset provided and uploaded to Huggingface for easier access.

2. T5_Inference.ipynb: This notebook is designed for direct inference using the fine-tuned model from Huggingface. To ensure reproducibility, I’ve used the backed up older model, which is ready to run out of the box.

3. Development Process: This document outlines the steps and thought process behind the model development, including decisions on data processing, model selection, and fine-tuning.

How to Use
You can use any of the provided notebooks for testing the model on your own dataset. To do so:

Replace the .json file in the raw_datasets directory with your own dataset.
Run the chosen notebook for training or inference.
