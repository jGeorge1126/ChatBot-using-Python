# ChatBot using Python
 Simple chatbot using python and HTML, JavaScript frontend

## Step 1: Initialize
```bash
$ git clone https://github.com/jGeorge1126/ChatBot-using-Python.git
$ cd ChatBot-using-Python
$ python -m venv venv
$ . venv/bin/activate
```

## Step 2: Install dependencies
```bash
$ (venv) pip install Flask torch torchvision nltk
```
## Step 3: Install nltk package
```bash
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
## Step 4: Modify intents.json with different intents and responses as you want.
Run
```bash
$ (venv) python train.py
```
This will dump data.pth file. And then run the following command to test it in the console.
```bash
$ (venv) python chat.py
```
## Step 5: Run the app.py
```bash
$ (venv) python app.py
```
Will be launch on http://127.0.0.1:5000
