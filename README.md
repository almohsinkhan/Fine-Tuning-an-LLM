# Customer Review Sentiment Classifier

Fine-tuned BERT model for binary sentiment classification.

## Results

Model: bert-base-uncased

Validation Accuracy: 92.66%

Test Accuracy: 92.36%

## Approach

- BERT tokenizer
- Custom PyTorch Dataset
- Fine-tuning BertForSequenceClassification
- AdamW optimizer
- Cross entropy loss