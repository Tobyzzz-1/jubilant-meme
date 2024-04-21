# jubilant-meme
Unsupervised sentiment analysis performed on the twitter sentiment analysis dataset using lexicon and word-vectorization approach 
<br>
The twitter sentiment analysis dataset: https://www.kaggle.com/competitions/tweet-sentiment-extraction/data?select=train.csv
<br>
The Afinn lexicon used: https://www.kaggle.com/datasets/tobyvincent/afinn-lexicon
<br>
The Google universal-sentence-encoder for vectorization: https://www.kaggle.com/models/google/universal-sentence-encoder/tensorFlow2/universal-sentence-encoder
<br>
<h1>Approach</h1>
Approach is rather simple:
<p>+</p><ul>Use nltk.stopwords to remove stopwords from every tweet and present it as a list of emotionally meaningful words.</ul>
<p>+</p><ul>vectorize the entire tweet after removing stopwords along with the afinn lexicon.</ul>
<p>+</p><ul>Use cosine similarity to bring about the sentiment score by comparing same or similar words between the lexicon and the tweet.</ul>
<p>+</p><ul>A score greater than 0 can be cosidered to have a positive sentiment and that having lesser than 0 has a negative sentiment.</ul>
<style>
  p,ul{
  display:inline;  
  }
</style>



