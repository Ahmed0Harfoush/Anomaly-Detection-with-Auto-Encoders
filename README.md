# Anomaly-Detection-with-Auto-Encoders:

Class 0 (Normal) represents standard transaction behavior
Class 1 (Fraud) represents rare and abnormal patterns

Because fraudulent transactions are significantly fewer than normal ones, traditional supervised classification models may become biased toward predicting the majority class.

⚠️ Key Challenges
* Severe class imbalance
* Risk of high accuracy but poor fraud detection
* Minority class under-representation
* Threshold sensitivity


Anomaly Detection Using Autoencoder
To address the highly imbalanced nature of the fraud detection dataset, an Autoencoder-based anomaly detection approach is applied.
Instead of treating the problem as a traditional supervised classification task, the model is trained primarily on normal transactions (class 0) to learn typical behavioral patterns.
An Autoencoder consists of two main components:
* Encoder: Compresses input data into a low-dimensional latent representation.
* Decoder: Reconstructs the original input from this compressed representation.


Kaggle Notebook: https://www.kaggle.com/code/ahmed1harfoush/anomaly-detection-with-auto-encoders

Colab Notebook: https://colab.research.google.com/drive/1uh9pSezOACmtuBovwM46JMFIPirWMZUV?usp=sharing

![My Image](https://fraud-detection-handbook.github.io/fraud-detection-handbook/_images/autoencoder.png)

