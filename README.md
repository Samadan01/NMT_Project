# Neural Machine Translation (NMT_Project)
## Neural Machine Translation with Attention
This project aim to develop/build an English-to-German neural machine translation (NMT) model using Long Short-Term Memory (LSTM) networks with attention.
Machine translation is an important task in natural language processing and could be useful not only for translating one language to another but 
also for word sense disambiguation (e.g. determining whether the word "bank" refers to the financial bank, or the land alongside a river). 
Implementing this using just a Recurrent Neural Network (RNN) with LSTMs can work for short to medium length sentences but can result in vanishing gradients for very long sequences. 
Also the Attention mechanism added to it, will help solve the vanishing gradients and equip it to build a long sequences capturing all the dependencies.
