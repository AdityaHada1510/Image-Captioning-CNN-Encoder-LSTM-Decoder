🖼️ Image Caption Generator | CNN + LSTM + Attention

This project implements an AI-powered Image Caption Generator using a Convolutional Neural Network (CNN) as an encoder and an LSTM-based Recurrent Neural Network (RNN) as a decoder. 
The model is trained to generate human-like captions for images by learning from image-text pairs.


📌 Features

    Image feature extraction using pre-trained CNN (InceptionV3 / ResNet)

    Sequence modeling using LSTM-based decoder

    Attention mechanism for better alignment of visual context

    Text preprocessing and tokenization

    Custom training loop using TensorFlow / Keras

    Caption generation using greedy decoding or beam search

🧠 Model Architecture

    Image → CNN Encoder → Dense Embedding → LSTM Decoder ← Word Embedding
                                                 ↑
                                             Attention

📦Image-Captioning
-📜Image Captioning CNN Encoder LSTM Decoder.ipynb
- 📂Images/                  # The link to the images folder (https://www.kaggle.com/datasets/adityajn105/flickr8k)
- 📜captions.txt             # File with image filename and captions
- 📜requirements.txt         # Python package dependencies
- 📜README.md                # Project documentation

<img width="653" height="569" alt="1" src="https://github.com/user-attachments/assets/64a4dc89-4bc0-450d-b31f-d3f8fd5b2ace" />
<img width="680" height="563" alt="2" src="https://github.com/user-attachments/assets/40e8d06e-5aab-431a-9afb-5bf2310cf086" />


