# YouTube Comment Spam Detector

This project aims to develop a model capable of classifying spam comments on YouTube using machine learning techniques.
The analyses are carried out using both Python and R.

The first phase involves building the document-term matrix, which is implemented in Python.
We then move to R to perform descriptive statistics on the data and to build the initial, simpler classification models.

Once this step is completed, we return to Python to implement more computationally intensive models. First, I used TPOT to automatically identify the optimal machine learning pipeline for the classification task.
Finally, I built a neural network model.

All models are then compared to determine which one performs best.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietroParenti/youtube-comments-classifier/blob/main/SPAM.ipynb)
