# Russian Language Model

Russian language model is trained using the [fast.ai](http://www.fast.ai/) version of [AWD LSTM Language Model](https://arxiv.org/abs/1708.02182)--basically LSTM with droupouts--with data from [Lenta.ru](https://github.com/yutkin/lenta.ru-news-dataset). Achieved [perplexity](https://en.wikipedia.org/wiki/Perplexity) is **36.23** (90/10 validation split), compared to [state-of-the-art on November 17, 2017](https://github.com/RedditSota/state-of-the-art-result-for-machine-learning-problems) at **40.68** for English language. To the best of my knowledge, there is no comparable research in Russian language at the point of writing (May 8, 2018). Details can be found in the notebook `RLM.ipynb`. Model can be found on [Google Disk](https://drive.google.com/open?id=1gtIfMcu7q44q3aViepWE63WgsdY2Bjvn)

Similar model trained on [OpenSubtitles](http://www.opensubtitles.org/?) dataset got the second place at [Yandex Algorithm 2018 ML-track](https://github.com/ppleskov/yandex-algorithm-ml-track-2018)

# Language Model vs Embeddings

...

# To-do

* [ ] Train model on [wikipedia dump](https://dumps.wikimedia.org/ruwiki/latest/ruwiki-latest-pages-articles.xml.bz2)

