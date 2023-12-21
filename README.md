# English Question Answering with AdversarialQA Dataset

This repository contains code and resources for performing English Question Answering (QA) using the AdversarialQA dataset. The project involves utilizing mT5 and T5 models for question answering tasks and evaluating performance using various metrics like Character Error Rate (CER), Word Error Rate (WER), Exact Match (EM), BLEU Score, METEOR Score, and Rouge Score.

## Models Used
The primary models utilized in this project are the mT5 and T5 models, both of which are transformer-based models known for their success in natural language processing tasks.

## Metrics Calculated
- **Character Error Rate (CER)**: Measures the rate of character errors between predicted and target text.
- **Word Error Rate (WER)**: Calculates the rate of word-level errors in predicted and target text.
- **Exact Match (EM)**: Measures the accuracy of exact matches between predicted and target answers.
- **BLEU Score**: Evaluates the similarity between predicted and target text based on n-gram overlap.
- **METEOR Score**: Measures the quality of predicted text by considering synonyms and stemmed words.
- **Rouge Score**: Evaluates the overlap between predicted and reference text using recall, precision, and F1 score.

## Usage
1. **Setup**: Clone the repository and install the necessary dependencies listed in `requirements.txt`.
2. **Data Preparation**: Obtain the AdversarialQA dataset and preprocess it accordingly.
3. **Model Training**: Fine-tune the mT5 or T5 models on the prepared dataset for question answering.
4. **Evaluation**: Calculate the metrics - CER, WER, EM, BLEU, METEOR, and Rouge Score - using the provided evaluation scripts.
5. **Results and Analysis**: Interpret and analyze the model performance based on the obtained metrics.


## References
- AdversarialQA Dataset: [AdversarialQA Website](https://adversarialqa.github.io/)
- mT5 Model Documentation: [mT5 Model Documentation](https://huggingface.co/docs/transformers/model_doc/mt5)
- T5 Model Documentation: [T5 Model Documentation](https://huggingface.co/docs/transformers/model_doc/t5)


## Requirements

To set up the environment for running the code in this repository, install the required libraries using `pip`:

```bash
pip install -r requirements.txt


Feel free to contribute by forking the repository, creating pull requests, or reporting issues.
