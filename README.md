# Sensitive Text Clustering
Author: Lorenzo Balzani

`balzanilo[at]icloud[dot]com`

This code was originally intended to be the outcome of a challenge for an NLP-focused internship.

## Problem statement
Given a dataset where each sentence (by human judgment) provides some sensitive personal information about a person, write an ML algorithm that clusters data into different types of sensitive personal information and automatically assigns a label to each cluster.

Use Jupyter notebook and Python 3.X.

Hints:
* focus on SOTA approaches, try to avoid ancient technology if there is a better one.
* write clean code, it will be evaluated.
* write a conclusion to your findings.

## Notes
### GPU usage
I have chosen to use Google Colab because a GPU is freely available. Hence, it will be assumed that a GPU is available. If not, some packages might either not work (CuML) or be slower (BERTopic). You can fix this by using the *standard* package versions.

### Visualizations
All the visualizations (both interactive and static) cannot approprietaly be rendered in the notebook. Therefore, you might want to re-run the notebook to get them.

### Fine-tuned model
If you are not keen to re-train the model, download the `sensitive-text-clustering` model from the [HuggingFace Hub](https://huggingface.co/balzanilo/sensitive-text-clustering).
