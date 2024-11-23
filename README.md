# **Building All Classical NLP Models from Scratch**

This project is my personal journey to implement classical NLP and Transformer-based models from scratch, inspired by foundational and cutting-edge research papers. The goal is to deepen my understanding by coding these architectures "the old-fashioned way"—without relying on external human or LLM assistance. 

I will document the evolution of each model here, along with the associated challenges, improvements, and bugs. You’ll find multiple versions (e.g., `version1`, `version2`...) representing the historical development of the implementations.

---

## **Motivation and Scope**

Based on the latest research and my current understanding, I plan to enhance the models iteratively. While I recognize that my resources (e.g., data, GPUs) limit comprehensive training and evaluation, I aim to demonstrate the key improvements proposed in these foundational articles. 

### **Current Models Under Development**
1. **Decoder Prediction Models** (GPT2)
2. **Differential Transformer** (new attention trick)
3. **Vision Transformers (ViT)**
4. **Machine Translation Models** (Transformer)
6. **Small BERT Model** (with masking, randomly selecting tokens to mask)

---

## **Planned Workflow**

### **Implementation Roadmap**
I plan to implement and refine the following papers:
1. **Attention Is All You Need** – The foundation of Transformers.
2. **GPT-2** – Starting with a basic implementation, followed by enhancements.
3. **Vision Transformers (ViT)** – Adapting Transformer-based architectures for vision tasks.
4. **Differential Transformer** – Incorporating the novel attention mechanism discussed in the referenced article.
5. **MAMBA Architecture** – An advanced architecture (details forthcoming).

---

## **Training and Datasets**
- **Text Generation Models (e.g., GPT, Decoder)**: I will use Shakespeare's dataset provided by Andrej Karpathy as the primary training dataset.
- **Vision Models**: I am still deciding on a suitable small dataset for training lightweight vision models.

### **Hardware and Training Constraints**
Given the limited availability of GPUs, all models will be trained on small datasets and reduced architectures for shorter durations. Despite these constraints, the goal is to highlight the improvements proposed in the referenced papers.

---

## **Goals **
This project is a hands-on effort to:
1. Understand the inner workings of classical and modern NLP architectures.
2. Code these models step-by-step, testing my knowledge without relying on external help.
3. Share even incomplete or buggy code to showcase the learning process and evolution of the implementations.


