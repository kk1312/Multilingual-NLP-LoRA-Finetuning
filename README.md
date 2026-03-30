# Multilingual-NLP-LoRA-Finetuning
Finetuning of Gemma model for sentiment classification of multilingual Indian language dataset.

This was submitted as coursework for Deep Learning Practice in the IITM BS degree. The task involved using Gemma 1B parameter model for sentiment classification of sentences in 13 Indian languages. Challenges included the small size of the dataset and limited compute power. The solution in this repository uses LoRA for finetuning the adaptor matrices built from the base model's attention layer matrices, and obtained a final test F1 score of 0.92 in the contest.
