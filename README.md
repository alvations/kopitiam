# Kopitiam

**[Updated Jul 2023]:** Here is the updated notebook on how to fine-tune a **Seq2Seq model with Huggingface Transformers**, (not presented publicly yet), 



This was the repository that host the notebook for the **Seq2Seq with PyTorch** session in Data Science SG meetup in January 2018. The original accompanying slides can be found on https://goo.gl/Lu6CxB and the 2018 original notebook is on https://github.com/alvations/kopitiam/blob/master/Kopitiam.ipynb


Problem
====

Ordering coffee in Singapore hawker centre and food court could result in some surprises:

![Kopitiam](https://blog.seedly.sg/_next/image/?url=https%3A%2F%2Fcdn-blog.seedly.sg%2Fwp-content%2Fuploads%2F2022%2F04%2F13174522%2F141222-How-to-Order-Coffee-Kopi-in-Singapore-Like-Locals-Differences-in-Prices.png&w=3840&q=75)


Content
====

**Code:**

 - [How to Fine-Tune an OPUS Machine Translation Model?]()



Acknowledgements
----

The dataset used in this exercise is hosted on https://www.kaggle.com/alvations/sg-kopi



<!--
Archival Purpose Only
====

### Code:
 
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

### Requirements:

Python 3.6 (preferrably), otherwise Python3 should work too... 

```
gensim==3.2.0
nltk==3.2.5
pandas==0.22.0
torch==0.3.0.post4
torchvision==0.2.0
```

### Acknowledgement:

The materials of this notebook and the accompanying slides are largely based on the 

 - [PyTorch Seq2Seq tutorials by Sean Robertson](http://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html) and 
 - [Luong et al. tutorial on neural machine translation in ACL16](https://sites.google.com/site/acl16nmt/home).


-->
