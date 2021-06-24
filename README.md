# Fake News Detection

Fake news detection is a hot topic in the field of natural language processing. The objective of this project is to classify news as fake or real ones. This project deals with data analysis, visualization and classification.

## Dataset
Dataset exists in the repository in archive form, which I have downloaded from [kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset).


## Workdone

The text is tokenized and transformed using count vectorizer and tfidf transformer. The tokenized data is fed as input to the pipeline, and classified. Three classification models are used in this project.

* MultiNomial Naive Bayes
* Support Vector Machine
* Passive Aggressive Classifier

Performance evaluation metrics like accuracy and confusion matrix are used for evaluating the models. Achieved 99.6% accuracy. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
