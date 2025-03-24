# Fine-Tuning a Base Model Using LoRA

## Overview
This project demonstrates the fine-tuning of a base model using the concept of Low-Rank Adaptation (LoRA). The fine-tuning process is applied to Google Flan-T5 using financial news data from Kaggle: [PaulAdversarial/all_news_finance_sm_1h2023](https://www.kaggle.com/datasets/PaulAdversarial/all_news_finance_sm_1h2023).

## Workflow
1. **Pre-processing:** The dataset undergoes text pre-processing to clean and normalize the data.
2. **TF-IDF Analysis:** Term Frequency-Inverse Document Frequency (TF-IDF) is applied to extract key topics from the text, which serve as the ground truth for training.
3. **LoRA Fine-Tuning:** Google Flan-T5 is used as the base model, and LoRA is configured to fine-tune it with the processed dataset.
4. **Inference:** A script is provided to test the fine-tuned model after training in the last part of the notebook.

## Requirements
To run the notebook, install the following dependencies:
```bash
pip install transformers datasets peft
```

## Usage
Run the notebook in a suitable environment (such as Google Colab or Kaggle) to execute the fine-tuning process. After training, use the inference script to validate the model’s performance.

## License
This project is for educational and research purposes only.

