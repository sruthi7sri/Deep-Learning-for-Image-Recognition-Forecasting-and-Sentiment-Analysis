# Deep Learning for Image Recognition, Forecasting, and Sentiment Analysis

## Overview
This project presents a full-scale exploration of modern deep learning architectures including Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM), and advanced variants like ResNet and ResNeXt. It tackles a variety of tasks from image classification and vanishing gradient analysis to time-series forecasting and sentiment analysis, all implemented from scratch using PyTorch.

## Methodology

### Part 1: CNN Architectures (VGG-16 & ResNet-18)
- Implemented VGG-16 (Version C) and ResNet-18 from scratch using PyTorch.
- Used a 3-class image dataset (dogs, cars, food).
- Applied techniques like dropout, weight initialization (Xavier/He), and learning rate scheduling.
- Compared performance and visualized evaluation metrics (confusion matrix, F1 score, etc.).

### Part 2: Vanishing Gradient Demonstration
- Built a deeper version of VGG to observe vanishing gradients.
- Used PyTorch hooks to track gradient norms across layers.
- Compared with ResNet-18 to demonstrate the effectiveness of residual connections.

### Part 3: Time-Series Forecasting using RNN/LSTM
- Applied RNN and LSTM models on a real-world sequential dataset.
- Tuned hyperparameters and analyzed training/validation performance.
- Evaluated using MAE, RMSE, and visual plots.

### Part 4: Sentiment Analysis using LSTM
- Worked on text datasets (e.g., Amazon/Yelp/Twitter).
- Compared baseline and improved LSTM models with bidirectional layers and pre-trained embeddings.
- Evaluated via accuracy, confusion matrix, and F1 score.


### Bonus - Advanced Architectures
- Implemented ResNeXt using grouped convolutions.
- Performed transfer learning using pretrained MobileNet, InceptionV3, and ShuffleNet on Food-11.

---

## Real-World Applications
- Autonomous Systems: Image recognition using CNNs for vehicles, drones, etc.
- Forecasting Models: RNN/LSTM-based prediction for energy, traffic, and finance.
- NLP Pipelines: Sentiment-aware systems in e-commerce and customer service.
- AI Education: Covers fundamental to advanced deep learning use cases.

## Technology Comparison

| Component         | Chosen Technology                | Alternatives      | Rationale                                                   |
| ----------------- | -------------------------------- | ----------------- | ----------------------------------------------------------- |
| Framework         | PyTorch                          | TensorFlow, Keras | Flexible, dynamic graph, strong community support           |
| CNN Architectures | VGG-16, ResNet-18                | AlexNet, DenseNet | Great balance of performance and complexity                 |
| RNNs              | LSTM (stacked, Bi-LSTM)          | GRU, Transformers | Handles long-term dependencies better than vanilla RNN      |
| Transfer Learning | MobileNet, Inception, ShuffleNet | EfficientNet, VGG | Lightweight, fast training, effective in low-data scenarios |

---

## 📁 Repository Structure
```bash
Deep-Learning-for-Image-Recognition-Forecasting-and-Sentiment-Analysis/
├── notebooks/
│ ├── 01_cnn_vgg_resnet.ipynb
│ ├── 02_vanishing_gradients.ipynb
│ ├── 03_timeseries_rnn_lstm.ipynb
│ ├── 04_sentiment_analysis_lstm.ipynb
│ └── bonus/
│ ├── 06_bonus_resnext.ipynb
│ └── 07_bonus_transfer_learning.ipynb
├── requirements.txt
├── model_weights_links.txt
├── dataset_links.txt
└── README.md
```

## Running the Project

1. Clone the repository:
```bash
git clone https://github.com/sruthi7sri/Deep-Learning-for-Image-Recognition-Forecasting-and-Sentiment-Analysis.git
cd Deep-Learning-for-Image-Recognition-Forecasting-and-Sentiment-Analysis
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Run the Jupyter notebooks:
```bash
jupyter notebook
```

---

## Project Goals

* Develop, train, and evaluate deep learning architectures from scratch.
* Demonstrate the vanishing gradient issue and how ResNet solves it.
* Apply RNN/LSTM to sequential prediction tasks.
* Perform end-to-end sentiment analysis with text preprocessing and embedding layers.
* Visualize model performance using confusion matrices, precision-recall-F1, and learning curves.

---

## Collaborators

- Sruthisri Venkateswaran
- Darshan Sonawane

---
## License

© 2025 Sruthisri Venkateswaran and Darshan Sonawane. All rights reserved.
Educational use only.

---

## 📩 Contact

If you'd like to collaborate, ask questions, or share feedback, feel free to reach out via [GitHub Issues](https://github.com/sruthi7sri/Deep-Learning-for-Image-Recognition-Forecasting-and-Sentiment-Analysis/issues).

---
