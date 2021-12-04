# Running the Answers NLP example

Setup a Python 3.8+ virtual environment using your method of choice
then install the dependencies.

```
$ pip install pip -U
$ pip install -r requirements.txt
```

Override the nltk search path and run jupyter.

```
$ export NLTK_DATA=./data/nltk_data

$ jupyter lab
```

References

Based on work by [Satish Kumar](https://www.kaggle.com/klmsathishkumar/find-your-answers-here/notebook)

Instructions for installing the [NLTK Data](https://www.nltk.org/data.html)
