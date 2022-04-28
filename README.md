# ChatBot using Python
 Simple chatbot using python and HTML, JavaScript frontend

Step 1: Initialize
$ git clone https://github.com/jGeorge1126/ChatBot-using-Python.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ . venv/bin/activate

Step 2: Install dependencies
$ (venv) pip install Flask torch torchvision nltk

Step 3: Install nltk package
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')

Step 4: Modify intents.json with different intents and responses as you want.
Run
$ (venv) python train.py

This will dump data.pth file. And then run the following command to test it in the console.
$ (venv) python chat.py

Step 5: Run the app.py
$ (venv) python app.py

Will be launch on http://127.0.0.1:5000
