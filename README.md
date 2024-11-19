# Bi-Encoder_Zero_Shot_Classification
Zero shot Classification using Siamese Networks

## 1st Approach MLM Fine-Tuning of BERT model

- Limitations : Needs additionnal heuristics
- Cannot be used on models without the vocab containing a `[MASK]` token, or architecture not pre-trained on MLM or similar tasks, such as (FlauBERT, etc...)


The approach will be as follow :
1. Generate arouand 40k high quality (sentence, labels) samples for classification fine-tuning
2. 
