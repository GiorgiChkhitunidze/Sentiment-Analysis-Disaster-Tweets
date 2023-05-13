# Sentiment Analysis using Kaggle Disaster Tweets dataset

<p> This repository is my first sentiment analysis project. For this project I used <i><a href="https://www.kaggle.com/competitions/nlp-getting-started/data">Tweets dataset</a></i> from NLP competition on Kaggle. I used BERT language processing model to tokenize text and built a small NN model to train it. Eventually got 81% accuracy on test set.</p>


<p><b>The <i>main</i> notebook consists of:</b></p>

- Exploratory data analysis (EDA)
- Preprocessing data
- Setting up Dataset and DataLoader (which also tokenizes text with bert tokenizer)
- Building neural model and training
- Final Prediction and Visualization of results


<p><b>To view the <i>main</i> notebook without any rendering issues follow this <i><a href="https://nbviewer.org/github/GiorgiChkhitunidze/Sentiment-Analysis-With-Disaster-Tweets/blob/main/main.ipynb">link</a></i></b></p>
<p>Had to share the trained model weights through Dropbox as its size is more than 1 GB. You can Follow the <i><a href="https://www.dropbox.com/s/xwzg1qxkxz0rz3c/model_20.pt?dl=0">link</a></i> if you want to dowload.</p>



## Acknowledgements to these authors:
- Took some insights about cleaning tweets from this <a href="https://www.kaggle.com/code/marcovasquez/basic-nlp-with-tensorflow-and-wordcloud">kaggle notebook</a>. 
- Big thanks to this author for a handy set of <a href="https://www.kaggle.com/code/sandhyakrishnan02/nlp-with-disaster-tweets-using-lstm#9.-Text-Preprocessing">abbreviations</a>.
- Another great dictionary of <a href="https://www.kaggle.com/code/tuckerarrants/bert-with-huggingface-transformers/notebook#0.-Preprocessing">contractions</a>.
- Thanks to this author from <i>medium.com</i> for <a href="https://medium.com/geekculture/text-preprocessing-how-to-handle-emoji-emoticon-641bbfa6e9e7">emoji removal code</a>.
