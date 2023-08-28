# NLP based Chatbot in PyTorch

## Installation

### Create an environment

Whatever you prefer (e.g. conda or venv)

```
mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

### Activate it

```
venv\Scripts\activate
```

### Install PyTorch and dependencies

For Installation of PyTorch see official website.

You also need nltk:
```
pip install nltk
```
If you get an error during the first run, you also need to install nltk. tokenize.Punkt: Run this once in your terminal:

```
$ python
>>> import nltk
>>> nltk.download('punkt')
```

# Dependency
Install all the required dependencies mentioned in the recommended modules

### Usage

Run - This will dump data.pth file. And then run
```
python train.py
```
This will be an open command-based chat with ChatBot
```
python chat.py
```
For Run Flask in Website 
```
python app.py
```



