
#  HIDS using CNN-LSTM and Reinforcement Learning

A Host-based Intrusion Detection System (HIDS) developed as a minor project using a hybrid **CNN-LSTM model** enhanced with **Reinforcement Learning (RL)** to detect and classify cyber threats from host-level activity logs.

---

##  Project Overview

This project implements an intelligent HIDS that learns spatial-temporal features from system logs using CNN and LSTM. It is further refined with reinforcement learning to adaptively improve detection based on reward feedback. The model was trained on security datasets and evaluated for its accuracy, recall, and generalization.

---

##  Tech Stack

- Python
- TensorFlow / Keras
- CNN + LSTM Architecture
- Reinforcement Learning (Q-Learning / DQN)
- Matplotlib, NumPy, Pandas

---

##  Folder Structure

```

HIDS-Project/
├── dataset/                # Sample input data or CSV files
├── models/                 # Saved trained models
├── scripts/                # Preprocessing, training, evaluation
├── utils/                  # Helper functions (e.g., feature extraction)
├── results/                # Accuracy curves, confusion matrices
├── report/                 # Final project report (PDF)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies

````

---

##  How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/hids-rl-cnn-lstm.git
cd hids-rl-cnn-lstm

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run preprocessing and training
python scripts/train_rl_agent.py

# 4. Evaluate the model
python scripts/evaluate_model.py
````

---

##  Results

* Achieved \~93% test accuracy on benchmark dataset
* RL integration improved rare-class recall by 6%
* Stable convergence across epochs with minimal overfitting

---
