# AI3-Project - Amigo 

![](title.PNG)

Link to the Recording: https://drive.google.com/drive/folders/1w2Vmk60USbBZaFDEZrwnmoZnUOqGrhRm?usp=sharing

DialoGPT-based Chatbot that listens to you and your emotion. 

### Problem Statement
+ Most chat-bots that we have seen so far extract emotion from the text. Missing out on the tone in which the statement is put across. To tackle this, we have developed a chatbot that responds to the most important aspect of communication, ie. the tone.
+ Another challenge is bias in text data. In order to curb so, we looked at debiasing word embeddings from GLoVe to understand methodologies.

### Our Approach

We have built a chatbot that takes in the input of audio, accordingly responds based on emotion and content. Whilst doing so, we realized bias that existed in the responses. Hence, we also explored on how we could debias word embeddings, taking into account GLoVe embeddings. 

The models/algorithms we used included transfer learning of VGG16 for emotion detection, DialoGPT2 for chatbot responses and the neutralizing & equalizing algorithm for debiasing. We have also developed along the way an app that visually shows the embeddings in latent space.

A look at our streamlit app - 
![](app.gif)

### References & Credits
+ https://github.com/dkajtoch/glove_streamlit
+ https://github.com/karanbhatia5757/Debiasing-Word-Embeddings-For-Gender-Equality/blob/master/Debiasing%20Word%20Embeddings.ipynb
+ https://arxiv.org/abs/1607.06520
+ https://huggingface.co/transformers/model_doc/dialogpt.html


