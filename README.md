# word2vec
This project demonstrates the core mechanics of word embeddings—forward passes, backpropagation, and weight updates, without the use of modern ML frameworks.

# Dataset: Apache Derby Bug Reports
The model is trained on the Derby_Original_train.csv dataset.

**Source**: Software bug reports including summaries and descriptions.
**Preprocessing**: The text is cleaned, lowercased, and tokenized. We combine the "Summary" and "Description" fields to provide a rich context for the embeddings.