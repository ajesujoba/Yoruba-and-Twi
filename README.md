## Massive vs. Curated Word Embeddings for Low-Resourced Languages. The Case of Yorùbá and Twi

In the paper, we presented curated word and contextual em-beddings for Yorùbá and Twi. For this purpose, we gatherand select corpora and study the most appropriate techniques for the languages. We also create test sets for theevaluation of the word embeddings within a word similarity task (wordsim353) and the contextual embeddings within a NER task. The Corpora are available here while the embeddings and test sets are available in <a href="https://drive.google.com/drive/folders/1jkwLBkxJhnfVvf1yd7PyZw0nY8aNYaNN?usp=sharing">here</a>. 


For the comparison, we define 3 datasets according to the quality and quantity of textual data used for training: 
1. Curated Small Dataset (clean),C1, about 1.6 million tokens for Yorùbá and over 735 ktokens for Twi. The clean text for <a href="https://drive.google.com/drive/folders/1jkwLBkxJhnfVvf1yd7PyZw0nY8aNYaNN?usp=sharing">Twi</a> is the Bible and for <a href="https://drive.google.com/drive/folders/1jkwLBkxJhnfVvf1yd7PyZw0nY8aNYaNN?usp=sharing">Yorùbá</a> all texts marked under the C1 column in Ta-ble 1. 
2. In Curated Small Dataset (clean + noisy), C2,we add noise to the clean corpus (Wikipedia articles for Twi, and BBC Yorùbá news articles for Yorùbá). This increases the number of training tokens for Twi to 742 k tokens and Yorùbá to about 2 million tokens. 
3. Curated Large Dataset, C3 consists of all available texts we are ableto crawl and source out for, either clean or noisy 

Data set from the Niger Volta-Language Technology Institute can be gotten<a href="https://github.com/Niger-Volta-LTI/yoruba-text"> here  </a>
