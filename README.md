# Internship_nitw
Hybrid LSTM–Autoencoder-based LFA detection in Software Defined Networks (SDN). This project analyses network traffic, identifies abnormal patterns, and detects potential Low-Rate Link Flooding Attacks using deep learning techniques. Developed during an internship at NIT Warangal, it focuses on network security,and intelligent attack detection.



# Hybrid LSTM–Autoencoder Based LFA Detection in SDN

## Project Overview

This project focuses on detecting Low-Rate Link Flooding Attacks (LFAs) in Software Defined Networks (SDNs) using a Hybrid LSTM–Autoencoder Deep Learning model.

Low-Rate Link Flooding Attacks generate malicious traffic at a relatively low rate, making them difficult to distinguish from normal network traffic. This project aims to analyse network traffic patterns and identify abnormal activities to improve attack detection.

The proposed approach combines Autoencoders for learning traffic feature representations with Long Short-Term Memory (LSTM) networks for analysing sequential traffic patterns.

## Internship

**Organization:** National Institute of Technology (NIT), Warangal

**Domain:** Software Defined Networking and Deep Learning

## Objectives

- Understand SDN architecture and network traffic behaviour.
- Analyse normal and malicious network traffic.
- Perform data preprocessing and feature extraction.
- Develop a Hybrid LSTM–Autoencoder model.
- Detect normal traffic and LFA attack traffic.
- Evaluate the model using standard classification metrics.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Deep Learning:** TensorFlow / Keras
- **Data Visualization:** Matplotlib, Seaborn
- **Network Environment:** Mininet, Ryu Controller
- **Development Platform:** Google Colab

## Proposed Methodology

1. Network Traffic Analysis
2. Dataset Preparation
3. Data Preprocessing
4. Feature Extraction
5. Hybrid LSTM–Autoencoder Model Development
6. LFA Detection
7. Model Performance Evaluation

### Workflow

```text
SDN Network Traffic
        |
        v
Dataset Preparation
        |
        v
Data Preprocessing
        |
        v
Feature Extraction
        |
        v
Autoencoder
        |
        v
LSTM Network
        |
        v
LFA Detection
        |
        v
Performance Evaluation
```

## Dataset

The project uses SDN network traffic data containing normal and LFA attack records.

The dataset is used for training and evaluating the proposed detection model.

**Classification Categories:**
- Normal Traffic
- LFA Attack Traffic

*Note: Dataset files can be added separately or linked here if they are publicly available.*

## Model Architecture

The proposed model combines two deep learning components:

- **Autoencoder:** Learns compressed representations of network traffic features.
- **LSTM:** Learns sequential dependencies in network traffic data.

The hybrid approach aims to identify abnormal traffic patterns associated with LFA attacks.

## Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/SDN-LFA-Detection-Hybrid-LSTM-Autoencoder.git
```

Navigate to the project directory:

```bash
cd SDN-LFA-Detection-Hybrid-LSTM-Autoencoder
```

Install the required libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
```

## Execution

1. Open Google Colab or Jupyter Notebook.
2. Upload or connect the SDN traffic dataset.
3. Run the preprocessing and feature extraction steps.
4. Train the Hybrid LSTM–Autoencoder model.
5. Evaluate the model using the selected performance metrics.

## Future Enhancements

- Detect multiple types of LFA attacks.
- Integrate real-time SDN traffic monitoring.
- Improve detection performance using advanced deep learning techniques.
- Explore effective attack mitigation mechanisms.
- Evaluate the model using larger real-world network datasets.

## Author

**Pardha Saradhi Jella**

B.Tech – Artificial Intelligence and Data Science

## Acknowledgement

I would like to express my gratitude to the National Institute of Technology (NIT), Warangal, for providing the opportunity to explore Software Defined Networking, network security, and deep learning techniques through this internship.

---

*This project is developed for academic and research purposes.*
