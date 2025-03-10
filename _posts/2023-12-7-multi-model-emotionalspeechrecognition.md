---
title: "Multi-Modal Emotional Emotion Recognition"
date: 2023-10-11
categories: [Projects]
tags: [Machine Learning, Pattern Recognition, Transformers]
layout: single
author_profile: true
permalink: /projects/multi-model-emotionalspeechrecognition/
---

**Multi-Modal Emotional Emotion Recognition**

This project explores multimodal emotional speech recognition, aiming to improve emotion classification by integrating audio, text, and video data. Using the IEMOCAP dataset, which includes 10,039 samples of emotional expressions, we developed a model leveraging pre-trained transformers for each modality. The goal was to demonstrate the advantages of multimodal approaches over unimodal baselines in emotion recognition tasks.

Our methodology involved preprocessing the dataset (normalization, truncation, sampling frames) and constructing an end-to-end multimodal model. We employed late-fusion techniques for combining modality outputs and experimented with fine-tuning and freezing strategies to optimize performance.

**Technologies Used**

- **Programming Languages**: Python
- **Libraries \& Frameworks**: Hugging Face Transformers, PyTorch
- **Models**: Wav2Vec 2.0 (Audio), RoBERTa (Text), ViVit (Video)
- **Machine Learning Techniques**: Late-fusion, Transformer embeddings, Feed-forward networks
- **Data Handling**: Preprocessing, Tokenization, Normalization

**GitHub Repository**

For more details, check out the project repository on GitHub: [GitHub - MultimodalEmotionRecognition](https://github.com/DimitrisGkoutzounis/MultimodalEmotionRecognition.git)