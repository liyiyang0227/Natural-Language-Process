# Translation Quality Estimation
We designed 3 different models to predict the translation quality score of a English-Chinese sentence pair. All models are run in Jupyter notebook. We recommand you to use Colab if you don't have a GPU in your device. Because our models are run in GPU.
## Prerequisites
Before using the model, you need to install the following libraries.<br/>
numpy, torchtext, spacy, nltk, gensim, jieba, torch, scipy, tqdm, urllib, math, sklearn<br/>
You also need to install some zip files, though they are all contain in the Juypter notebook. You don't have to install them if you run in Jupyter notebook<br/>
```bash
!spacy download en_core_web_md
!spacy link en_core_web_md en300

!wget -c https://github.com/Tony607/Chinese_sentiment_analysis/blob/master/data/chinese_stop_words.txt
!wget -O zh.zip http://vectors.nlpl.eu/repository/20/35.zip
!unzip zh.zip 

!pip install bert-serving-client
!pip install -U bert-serving-server[http]
!wget https://storage.googleapis.com/bert_models/2018_11_03/chinese_L-12_H-768_A-12.zip
!unzip chinese_L-12_H-768_A-12.zip
!wget https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip
!unzip uncased_L-12_H-768_A-12.zip
```
## Models
We upload 4 Jupyter notebooks and each contains the corresponding model. You can follow the text in each file to train and test the model. But be careful, some models like the RNN file has two sub-models in it. You need to run the corresponding blocks to correctly train and test the model.

## Authors
Yichong Chen email: yc3919@ic.ac.uk.<br/>
Yiyang Li email: yl1319@ic.ac.uk<br/>
Zifeng Niu email: zn19@ic.ac.uk
