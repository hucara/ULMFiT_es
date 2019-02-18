# ULMFit ES
This repository contains implementations of [ULMFit](https://arxiv.org/abs/1801.06146) by Jeremy Howard and Sebastian Ruder applied to NLP tasks for the Spanish Language.

Francisco Ingham [project](https://github.com/fpingham/SpanishULMFit)  for *Classification of Spanish Tweets as of 2017 in the GeneralTASS Dataset* was used as a starting point for hyperparameter tuning.

This approach would have achieved SOTA for the [ 1st Classification of Spanish Election Tweets Task at IberEval 2017](http://ceur-ws.org/Vol-1881/Overview2.pdf). 

20% of the data are held out as a validation set.

 84% accuracy is achieved only using the provided competition data (see [notebook](https://github.com/adai183/ULMFiT_es/blob/master/only_competition_data.ipynb)).

After using additional unlabeled data for language model fine-tuning  the model scores 91% accuracy (see [notebook](https://github.com/adai183/ULMFiT_es/blob/master/add_campaign_2016_data.ipynb)).