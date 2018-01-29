# Kopitiam

This is the repository that host the notebook for the **Seq2Seq with PyTorch** session in Data Science SG meetup in January 2018. The accompanying slides to this notebook repo can be found on https://goo.gl/Lu6CxB


Problem
====

Ordering coffee in Singapore hawker centre and food court could result in some surprises:

![Kopitiam](https://static.straitstimes.com.sg/sites/default/files/160522_kopi.jpg)


Content
====

**Code:**

 - [Kopitiam.ipynb](https://github.com/alvations/kopitiam/blob/master/Kopitiam.ipynb)

**Pre-trained Models:**

 - *Vanilla RNN Encoder-Decoder model*
   - `encoder_vanilla_100_100000.pkl`
   - `decoder_vanilla_100_100000.pkl`
 - *Vanilla RNN Encoder-Decoder model with teacher forcing*
   - `encoder_vanilla_100_100000_0.5.pkl`
   - `decoder_vanilla_100_100000_0.5.pkl`
  - *Attention RNN Encoder-Decoder model with teacher forcing*
   - `encoder_attention_100_100000_0.5.pkl`
   - `decoder_attention_100_100000_0.5.pkl`

Requirements
====

Python 3.6 (preferrably), otherwise Python3 should work too... 

```
gensim==3.2.0
nltk==3.2.5
pandas==0.22.0
torch==0.3.0.post4
torchvision==0.2.0
```



Acknowledgements
----

The dataset used in this exercise is hosted on https://www.kaggle.com/alvations/sg-kopi

The materials of this notebook and the accompanying slides are largely based on the 

 - [PyTorch Seq2Seq tutorials by Sean Robertson](http://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html) and 
 - [Luong et al. tutorial on neural machine translation in ACL16](https://sites.google.com/site/acl16nmt/home).


