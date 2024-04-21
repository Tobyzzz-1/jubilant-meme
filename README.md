# jubilant-meme
Unsupervised sentiment analysis performed on the twitter sentiment analysis dataset using lexicon and word-vectorization approach 
The twitter sentiment analysis dataset: https://www.kaggle.com/competitions/tweet-sentiment-extraction/data?select=train.csv
The Afinn lexicon used: https://www.kaggle.com/datasets/tobyvincent/afinn-lexicon
The Google universal-sentence-encoder for vectorization: https://www.kaggle.com/models/google/universal-sentence-encoder/tensorFlow2/universal-sentence-encoder

<h1>Approach</h1>
Approach is rather simple:
     <ul>Use nltk.stopwords to remove stopwords from every tweet and present it as a list of emotionally meaningful words.</ul>
     <ul>vectorize the entire tweet after removing stopwords along with the afinn lexicon.</ul>
     <ul>Use cosine similarity to bring about the sentiment score by comparing same or similar words between the lexicon and the tweet.</ul>
     <ul>A score greater than 0 can be cosidered to have a positive sentiment and that having lesser than 0 has a negative sentiment.</ul>
