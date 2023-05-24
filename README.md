# Sentiment Analysis using Kaggle Disaster Tweets dataset

<p> This repository is my first sentiment analysis project. The job was to predict which Tweets are about real disasters and which ones are not. I used BERT language processing model to tokenize tweets and built a small NN model to fine tune BERT pretrained model. Eventually got 81% accuracy on test set.</p>


<p><b>The <i>main</i> notebook consists of:</b></p>

- Exploratory data analysis (EDA)
- Preprocessing data
- Setting up Dataset and DataLoader (which also tokenizes text with bert tokenizer)
- Building neural model and training
- Final Prediction and Visualization of results


<p><b>Click here on <a href="https://nbviewer.org/github/GiorgiChkhitunidze/Sentiment-Analysis-With-Disaster-Tweets/blob/main/main.ipynb"><i>main.ipynb</i></a> to view notebook without any rendering issues.</b></p>



## Acknowledgements & References:
- <a href="https://www.kaggle.com/competitions/nlp-getting-started/data">"Natural Language Processing with Disaster Tweets"</a> by Kaggle
- Took some great insights about cleaning tweets from this <a href="https://www.kaggle.com/code/marcovasquez/basic-nlp-with-tensorflow-and-wordcloud">kaggle notebook</a>. 
- Big thanks to this author for a handy set of <a href="https://www.kaggle.com/code/sandhyakrishnan02/nlp-with-disaster-tweets-using-lstm#9.-Text-Preprocessing">abbreviations</a>.
- Another great dictionary of <a href="https://www.kaggle.com/code/tuckerarrants/bert-with-huggingface-transformers/notebook#0.-Preprocessing">contractions</a>.
- Thanks to this author from <i>medium.com</i> for <a href="https://medium.com/geekculture/text-preprocessing-how-to-handle-emoji-emoticon-641bbfa6e9e7">emoji removal code</a>.
