# sentiment-analysis-CNN-LSTM
IMDb review sentiment analysis model created in TensorFlow with CNN+LSTM+GloVe Twiter Embeddings. The model takes in movie review as a string and output a decimal between 0 and 1, representing the sentiment of the review toward the movie. The data consists of 50k IMDb movie reviews splited into 7/1/2 training/validation/testing set.
<br><br>
## Input Data
Input data are taken from https://www.kaggle.com/ducanger/imdb-dataset. <br>
In this project, the punctuations are taken out from the data as part of the data preprocessing.<br>
![input](https://user-images.githubusercontent.com/31713252/132416994-940815fa-c57a-4aa2-9213-855a94d7623e.jpg)
<br><br>
## Word Embedding
This model uses the GloVe pretrained word embeddings.<br>
(Twitter 200d, can be found here:https://nlp.stanford.edu/projects/glove/)
<br><br>
## Model
![model](https://user-images.githubusercontent.com/31713252/132417398-a99a2130-0aa6-4eec-9006-a0c11c4d4bd0.jpg)
<br><br>
## Model Evaluation
The model achieved 91.36% validation accuracy on its best epoch, with a 91.21% test accuracy.<br>
![accuracy](https://user-images.githubusercontent.com/31713252/132417595-ae23ba1c-e7a1-4798-9cfc-5d2b78593a30.png)


