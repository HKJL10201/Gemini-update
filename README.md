# Gemini Update

An updated version of [Gemini](https://github.com/xiaojunxu/dnn-binary-code-similarity).

New features:
- Now support Python 3.
- Now support Tensorflow 2.

# Original README

# DNN Binary Code Similarity Detection
This repo provides an implementation of the Gemini network for binary code similarity detection in [this paper](https://arxiv.org/abs/1708.06525).

## Prepration and Data
Unzip the data by running:
```bash
unzip data.zip
```

The network is written using Tensorflow 1.4 in Python 2.7. You can install the dependencies by running:
```bash
pip install -r requirements.txt
```

## Model Implementation
The model is implemented in `graphnnSiamese.py`.

Run the following code to train the model:
```bash
python train.py
```
or run `python train.py -h` to check the optional arguments.

After training, run the following code to evaluate the model:
```bash
python eval.py
```
or run `python eval.py -h` to check the optional arguments.
