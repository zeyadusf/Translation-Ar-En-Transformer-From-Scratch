
<div align="center">
  
  # Translation Ar En Transformer From Scratch
This project aims to build a Transformer from scratch and create a basic translation system from Arabic to English.

  <img src="https://github.com/user-attachments/assets/8ef50001-c577-465e-8114-e8fb6bbf0fba" width="300" alt="Transformer Architecture">
</div>


<p>
The Transformer is a deep learning model architecture introduced in the paper "Attention Is All You Need" by Vaswani et al. in 2017. It has revolutionized the field of natural language processing (NLP) and other areas like machine translation, text summarization, and more. The key innovation of the Transformer is the use of self-attention mechanisms, allowing it to process input data in parallel and capture complex dependencies between elements in the sequence, regardless of their distance from one another.

### Key Components of the Transformer:

1. **Self-Attention Mechanism**:
   - Self-attention, or scaled dot-product attention, calculates a set of attention scores for each word in the input sequence, determining how much attention should be paid to each word when encoding the current word. This mechanism enables the model to focus on relevant parts of the input for each word and capture relationships between words at any distance.

2. **Positional Encoding**:
   - Since the Transformer does not inherently capture sequence order due to its parallel processing nature, positional encoding is added to the input embeddings to provide information about the positions of words in the sequence.

3. **Encoder-Decoder Structure**:
   - The Transformer consists of an encoder and a decoder. The encoder processes the input sequence and generates a context-aware representation, while the decoder uses this representation to generate the output sequence.
   - The encoder and decoder are composed of multiple identical layers. Each layer in the encoder consists of two main components: a multi-head self-attention mechanism and a position-wise fully connected feed-forward network. The decoder layers also have an additional multi-head attention mechanism that attends to the encoder's output.

4. **Multi-Head Attention**:
   - Instead of a single attention mechanism, the Transformer uses multiple attention heads, allowing the model to jointly attend to information from different representation subspaces at different positions.

5. **Feed-Forward Networks**:
   - After the self-attention mechanism, the output is passed through a fully connected feed-forward network, applied independently to each position. This component helps to further process and transform the representation.

6. **Layer Normalization and Residual Connections**:
   - Each sublayer (attention or feed-forward) in the encoder and decoder is followed by layer normalization and has a residual connection around it, which helps in stabilizing and speeding up the training process.

### Applications:
The Transformer architecture is the foundation of many state-of-the-art models in NLP, such as BERT (Bidirectional Encoder Representations from Transformers), GPT (Generative Pretrained Transformer), and T5 (Text-to-Text Transfer Transformer). These models have achieved significant advances in various NLP tasks, including language translation, sentiment analysis, question answering, and more.


> Data on kaggle: [Arabic to English Translation Sentences](https://www.kaggle.com/datasets/samirmoustafa/arabic-to-english-translation-sentences) <br>
> Notebook on kaggle: [Translation Ar-En | Transformer From Scratch](https://www.kaggle.com/code/zeyadusf/translation-ar-en-transformer-from-scratch/notebook)
</p>
<br>
🚩 Because training Transformer from scratch requires a lot of datasets, GPUs, and a lot of experimentation in setting the appropriate hyperparameters, you will find the results of this model unsatisfactory for its use. 
<b>But this notebook is for <i>understanding the architecture of Transformer</i></b>.

<!--Social Media-->
<hr>

# :email: Contact #

<p align="center">
 <a href="https://www.facebook.com/ziayd.yosif" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-1877F2?style=flat&logo=facebook&logoColor=white" alt="Facebook" />
</a>

<a href="https://www.instagram.com/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-zeyadusf-white?style=flat&logo=instagram&logoColor=#E65468" alt="Instagram" />
</a>


<a href="https://www.linkedin.com/in/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

<a href="https://github.com/zeyadusf" target="_blank">
  <img src="https://img.shields.io/badge/-@zeyadusf-181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
</a>
