# Task 2

Submission:

1. Final submission is one zip with following files:
    - main jupyter notebook
    - requirement file (pip freeze)

---

Challenges:

2000 annotated (positive = 1; negative = 0) tweets about Bitcoin.

Tasks are:

1. Perform a sentiment analysis with various approaches
2. Compare the performance

---
Steps:

1. <span style="color: green;">Preprocess the text data</span>
    - take out the hastag
    - take out emoticon / non alphabetic
    - takeout https

2. <span style="color: green;">apply sentiment dictionary</span>

3. <span style="color: green;">Fit a TF-IDF vectorizer and a classifier of your choice (e.g. Logit)</span>

4. Train RNN Language classifier, including embeddings

5. Train the RNN language with pre-trained embeddings

6. pre-trained transfromer model (using huggingface pipeline)

7. Fine-tune the pre-trained transformer model 
    - use huggingface transformer library
    - since this is computationally intensive one epoch is sufficient and a lightweight model such as DistilBERT is recommended

8. Evaluation
    - create a suitable binray classification metrics
    - pack it in a summary table
