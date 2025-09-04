# 🧠 Small Language Model (SLM)

This repository contains a **Small Language Model (SLM)** implementation following by [Raj Dandekar’s tutorial](https://www.youtube.com/watch?v=pOFcwcwtv3k&t=9583s&ab_channel=Vizuara).  
The project walks through the essential steps of building and training a transformer-based model from scratch.

---

## 🚀 Project Overview

Large Language Models (LLMs) like GPT are powerful but resource-intensive.  
Here, we build a **simplified version** — a Small Language Model (SLM) — to learn the fundamentals of:

- Data preprocessing and tokenization  
- Efficient dataset storage on disk  
- Input-output batch creation for training  
- Transformer-based model architecture  
- Training with cross-entropy loss  
- Running inference to generate new text

---

  ## 📊 Workflow

1. **Pre-process Data**  
   - Tokenize the dataset into IDs  
   - Store token IDs on disk for efficiency  

2. **Create Input-Output Batches**  
   - Split tokens into fixed-length sequences  
   - Generate input and target pairs  

3. **Define Model Architecture**  
   - Embedding layer  
   - Transformer blocks with self-attention  
   - Output projection to vocabulary size  

4. **Loss Function**  
   - Cross-entropy loss for next-token prediction  

5. **Training Configuration**  
   - Hyperparameters (learning rate, epochs, batch size)  
   - Optimizer setup  

6. **Pre-train the Model**  
   - Train using batches  
   - Save checkpoints  

7. **Inference**  
   - Feed a prompt to the trained model  
   - Generate new tokens autoregressively  
