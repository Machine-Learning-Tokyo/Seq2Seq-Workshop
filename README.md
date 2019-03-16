# Seq2Seq-Workshop
Seq2Seq workshop materials

Presentation slides: [Intro to Sequence to Sequence Learning](https://docs.google.com/presentation/d/1Zz1VzDHhRiF-QGyn_v7fHTSyoEOK7CH4nq2YpyZpVaY/edit?usp=sharing)

<p align="left">
  <img src="https://github.com/Machine-Learning-Tokyo/Seq2Seq-Workshop/blob/master/seq2seq.png" width="700">
</p>
  
  
# Dependencies

* Python 3.6
* Pytorch 0.4.1
* MeCab with neologd dictionary
  - [Instructions for Mac](https://qiita.com/taroc/items/b9afd914432da08dafc8)
  - [Instructions for Ubuntu](https://qiita.com/ekzemplaro/items/c98c7f6698f130b55d53)


# Installation

1. Create a conda environment:
   ```
   conda env create -n seq2seq python=3.6
   ```
2. Install dependencies
   ```  
   pip install spacy
   pip install mecab-python3

   ```
3. Install Spacy `en` model:
   ```
   python -m spacy download en
   ```
4. Install Pytorch `0.4.1`:
   ```
   pip install torch==0.4.1
   ```
   
# Data

- English-Japanese Translation Corpus: (ftp://ftp.monash.edu/pub/nihongo/examples.utf.gz) 
- [COCO Image Captioning Dataset](http://cocodataset.org/#download) (2014 train/val set)
