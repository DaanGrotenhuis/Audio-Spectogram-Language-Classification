# Deep-Learning-Project
This project explores the use of Convolutional Neural Networks (CNNs) to classify spoken languages from raw audio clips by transforming them into spectrograms, a frequency-time representation well-suited for audio signal modeling. The aim was to build a lightweight and efficient deep learning pipeline that identifies language from short audio segments collected from YouTube—despite challenges like background noise, data imbalance, and recording variability.

Core Highlights:
- Input: YouTube-sourced audio data, normalized and transformed into spectrograms.
- Architecture: CNN with Leaky ReLU activation, dropout, and softmax output for multi-class classification.
- Hyperparameter tuning: Explored kernel size, learning rate, dropout, and weight decay to optimize F1-score.

Experiments Included:
- Spectrogram preprocessing techniques.
- Model sensitivity to dropout layers and weight decay.
- Comparison of performance across 3+ languages (French, Portuguese, Dutch).
- Confusion matrix analysis revealed strong predictions for French/Portuguese, but Dutch was misclassified due to potential class imbalance or under-extraction of key features.

Visualization:

<img width="1805" height="371" alt="image" src="https://github.com/user-attachments/assets/2c99f6b1-b2cb-4811-9d24-b87472e257c2" />
<img width="548" height="413" alt="image" src="https://github.com/user-attachments/assets/7201860a-6fb7-448b-a75d-d32e718bb07d" />

