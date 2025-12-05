#### Provided by Somayeh Komeylian: PhD Student at UCSD & SDSU ####
# Natural Language Processing (NLP) Model #

# Two Datasets
    # ✅ Shakespeare – loaded from TensorFlow link
    # ✅ Shahnameh (Persian epic poem) – loaded via KaggleHub

# RNN Text Modeling (from scratch): 
    # The RNN uses a self-supervised language modeling objective:
    # Each input sequence is paired with the next character (or token) from the same text. 
    # No manually labeled data is required.

# Tokenization Levels
    # An RNN (or LSTM/GRU) can model text at different tokenization levels:
        # Character-Level: Each character is a token; good for handling rare or unseen words.
        # Word-Level: Each word is a token; captures more semantic meaning but requires a larger vocabulary.
    # Here, we train a character-level RNN language model on the dataset. 

# References:
    # https://deeplearningwithpython.io/chapters/chapter15_language-models-and-the-transformer/ #
    # https://github.com/Alireza-Akhavan/transformers #
