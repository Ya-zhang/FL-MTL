# Federated Learning for MIBC Diagnosis

This repository contains the official PyTorch implementation of the paper:
**"[Federated Learning-Based Multi-Task Framework for Privacy-Preserving Diagnosis of Muscle Invasion in Bladder Cancer]"**

## 📋 Introduction
We propose a privacy-preserving Federated Learning framework for Muscle-Invasive Bladder Cancer (MIBC) diagnosis. The model simultaneously performs tumor segmentation and invasion classification using a multi-task learning architecture.

## 🚀 Usage

The main entry point for training is `server_classifiction.py`. This script manages the training loop, parameter configuration, and data loading.

### 1. Configuration
Before running, please open `server_classifiction.py` and modify the **dataset paths** (image and label directories) to match your local environment. You can also adjust hyperparameters (e.g., learning rate, `prox_mu`) directly in this file.

### 2. Execution
Start the training process with the following command:

```bash
python server_classifiction.py
