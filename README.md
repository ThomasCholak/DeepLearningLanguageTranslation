# Spanish-to-English Translation Project

Link to overleaf essay project: [here](https://www.overleaf.com/read/vqstzfqjcktn#64b090).

The purpose of this model is to utilize a transformer model in deep learning architecture to successfully translate from English to Spanish.

The model was broken into the standard 70% training data, 15% testing data and 15% valida-
tion data for my dataset. 83,276 sentence pairs were used for training, with 17844 sentence pairs
used for both testing and validation, respectively. The data was then encoded with positional
embeddings before being fed into a transformer-based architecture and was then decoded (also
using a Transformer).

After running my model for over an hour of training time on GPU, and utilizing a full 30
epochs, my model reached convergence at around 70 percent accuracy on the validation data set.
My model was accurate for the most part, but sometimes will miss a word or will not recognize
a token. Future plans for my model will include finding a way to host the model on my website
so that visitors to my web page will be able to interact with the model and possibly add to the
dataset as well if they choose to opt-in.

Respective validation and accuracy graphs:

![finalaccuracy](https://github.com/ThomasCholak/DeepLearningLanguageTranslation/assets/63080803/642eb85a-7aad-4eb0-8582-8d62734638ed)
![finalloss](https://github.com/ThomasCholak/DeepLearningLanguageTranslation/assets/63080803/2eab2879-81dd-42a4-bbce-03397afd1686)
