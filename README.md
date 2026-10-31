# Advanced Deep Learning

**A structured, hands-on exploration of modern deep learning architectures, techniques, and applications.**

This repository documents my learning journey through advanced deep learning, covering Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), Transformers, Mamba, Computer Vision, Natural Language Processing (NLP), and MLOps.

The focus is on developing a solid theoretical understanding, implementing core concepts, conducting experiments, and applying deep learning techniques to practical problems.

**Status:** In Progress  
**Curriculum:** 33 Videos · 7 Learning Modules  
**Primary Tools:** Python · PyTorch · Jupyter Notebook

---

## 1. Learning Objectives

The primary objectives of this repository are to:

- Understand the mathematical foundations and architectures of modern deep learning models.
- Implement and train neural networks for image, text, and sequential data.
- Explore advanced architectures such as Transformers, Vision Transformers, and Mamba.
- Evaluate model performance, generalization, and training strategies.
- Develop practical applications in Computer Vision and NLP.
- Learn experiment tracking, workflow orchestration, and CI/CD principles for machine learning.
- Document experiments, observations, and implementation details in a reproducible manner.

## 2. Curriculum

The learning materials are organized into seven modules.

| Module | Topic | Videos |
|---|---|---:|
| 01 | Convolutional Neural Networks | 8 |
| 02 | Recurrent Neural Networks | 4 |
| 03 | NLP & Transformers | 3 |
| 04 | Mamba & State Space Models | 3 |
| 05 | Vision Transformers & Multimodal AI | 4 |
| 06 | MLOps & AI Engineering | 6 |
| 07 | Teaching Assistant Exercises | 5 |
| **Total** | | **33** |

### Module 01 — Convolutional Neural Networks

- Introduction to CNN
- From MLP to CNN
- Training Convolutional Neural Networks
- Batch Normalization and Dropout
- CNN Training and Generalization
- Advanced CNN Architectures

**Focus:** Convolution operations, feature extraction, training optimization, regularization, and generalization.

### Module 02 — Recurrent Neural Networks

- Introduction to RNN
- RNN for Time-Series and Text
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

**Focus:** Sequential modeling, recurrent architectures, and long-term dependencies.

### Module 03 — NLP & Transformers

- Tokenization
- Embedding
- Transformer Encoder for Text Classification

**Focus:** Text representation, contextual embeddings, self-attention, and sequence classification.

### Module 04 — Mamba & State Space Models

- Mamba 1 — Part 1
- Mamba 1 — Part 2
- Mamba 2

**Focus:** Selective state space models, efficient sequence modeling, and modern alternatives to attention-based architectures.

### Module 05 — Vision Transformers & Multimodal AI

- Vision Transformer (ViT)
- Transformer for Images and Time-Series
- OCR Project using YOLO11 and CNN
- Visual Question Answering (VQA)

**Focus:** Vision-based Transformers, object detection, optical character recognition, and multimodal learning.

### Module 06 — MLOps & AI Engineering

- Apache Airflow for Workflow Scheduling
- MLflow for Model Tracking and Versioning
- Application Tracking and Logging
- CI/CD for Machine Learning Systems

**Focus:** Experiment management, reproducibility, workflow automation, and ML engineering practices.

### Module 07 — Teaching Assistant Exercises

- December 8, 2024 — Parts 1 & 2
- December 15, 2024
- December 22, 2024
- December 29, 2024

**Focus:** Practical exercises, implementation, and reinforcement of theoretical concepts.

---

## 3. Repository Structure

The repository follows a modular organization, with each directory representing a major learning area.

| Directory | Description |
|---|---|
| `01-convolutional-neural-networks/` | CNN foundations, training, and advanced architectures |
| `02-recurrent-neural-networks/` | RNN, LSTM, GRU, and sequence modeling |
| `03-nlp-transformers/` | Tokenization, embeddings, and Transformer encoders |
| `04-mamba-state-space-models/` | Mamba architectures and state space models |
| `05-vision-multimodal/` | Vision Transformers, OCR, and VQA |
| `06-mlops/` | Airflow, MLflow, logging, and CI/CD |
| `07-ta-exercises/` | Practice exercises and solutions |
| `assets/` | Supporting figures and visualizations |

Each topic may include:

- **Notes:** Theoretical explanations, mathematical derivations, and key takeaways.
- **Notebooks:** Interactive implementations and experiments.
- **Source Code:** Reusable Python modules and training utilities.
- **Exercises:** Practice problems and solutions.
- **Results:** Evaluation metrics, training curves, and experimental observations.

## 4. Development Environment

The repository primarily uses:

- **Language:** Python
- **Deep Learning Framework:** PyTorch
- **Experimentation:** Jupyter Notebook
- **Computer Vision:** OpenCV, Ultralytics
- **Experiment Tracking:** MLflow
- **Workflow Orchestration:** Apache Airflow
- **Version Control:** Git and GitHub

Dependencies will be documented as the individual modules are implemented.

## 5. Projects

The repository includes or plans to include the following practical projects.

| Project | Main Techniques | Status |
|---|---|---|
| CNN Image Classification | CNN, Regularization | Planned |
| Time-Series Forecasting | RNN, LSTM, GRU | Planned |
| Text Classification | Embeddings, Transformer Encoder | Planned |
| Optical Character Recognition | YOLO11, CNN, OCR | Planned |
| Visual Question Answering | Computer Vision, NLP, Multimodal Learning | Planned |
| ML Experiment Pipeline | MLflow, Airflow, CI/CD | Planned |

Each completed project will include its problem definition, methodology, experimental setup, evaluation results, and implementation instructions.

## 6. Learning Methodology

Each topic is approached through four stages:

1. **Theory:** Study the underlying concepts, architectures, and mathematical principles.
2. **Implementation:** Translate theoretical knowledge into working code.
3. **Experimentation:** Evaluate model behavior, compare configurations, and analyze results.
4. **Documentation:** Record observations, limitations, and lessons learned.

The goal is to move beyond running existing implementations toward understanding how and why these models work.

## 7. Progress

This repository is under active development as the curriculum is completed.

Learning progress and completed implementations will be updated throughout the project.

## 8. References

The repository is based on advanced deep learning lecture materials and supplemented with official documentation, research papers, and open-source implementations.

Additional references will be provided within the corresponding modules.

---

## License

License information will be added when the repository's distribution terms are finalized.