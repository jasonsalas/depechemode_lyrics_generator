# Depeche Mode lyrics generator
Using a neural network with LSTM layers to auto-generate text in the style and spirit of Depeche Mode. 

![It is about damn time](https://github.com/jasonsalas/depechemode_lyrics_generator/blob/master/nominees.jpg)

When I happily learned that Dave Gahan, Martin Gore, Andy Fletcher and the boys were FINALLY up for the Rock N Roll Hall of Fame as nominees, I was elated. And motivated to do something to honor people whose art has had such a profound and lasting influence on me.
I found the [55000+ Song Lyrics dataset on Kaggle](https://www.kaggle.com/mousehead/songlyrics), and filtered only the tracks by DM, discovering a discography of 167 recorded studio tracks. 

I isolated the column with only their lyrics, and began modified a very slick tutorial from MachineLearningMastery on [using natural language processing to generate text](https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/). What’s clever is that when appending all of Depeche Mode’s songs in the same text file, the size of the corpus is about as large as many longform texts in creative commons archives like [Project Gutenberg](https://www.gutenberg.org/).
