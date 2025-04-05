# Sentiment Analysis with Emotional Augmentation

## Overview
This repository presents an innovative sentiment analysis framework that boosts accuracy by augmenting text with emotional context. By integrating a text-to-text generation model (**Flan-T5-large**) with a contextual sentiment analysis model (**RoBERTa-base**), this approach achieves an impressive **98% accuracy** on sentiment classification tasks. The method employs a mixture-of-experts structure to enhance sentence-level sentiment understanding.

## Methodology
The pipeline consists of two key stages:
1. **Emotional Augmentation**:  
   - **Flan-T5-large** enriches original text (e.g., tweets or reviews) by injecting key emotional aspects, improving the expressiveness of the input.
2. **Sentiment Analysis**:  
   - The augmented text is analyzed by **RoBERTa-base**, a fine-tuned contextual model, to classify sentiment with high precision.

This hybrid approach outperforms traditional methods by leveraging both generative and discriminative capabilities.

## Datasets
- **Tested Datasets**:
  - **StanfordNLP/IMDB**: Movie reviews dataset for binary sentiment classification.
  - **US_Airline_Sentiment**: Twitter data on airline experiences for multi-class sentiment analysis.
- **Planned Dataset**:
  - **StanfordNLP/Sentiment140**: Large-scale Twitter dataset for sentiment analysis (work in progress).

## Key Features
- **Accuracy**: Achieves **97% overall accuracy** on tested datasets.
- **Models**:
  - Flan-T5-large (text augmentation).
  - RoBERTa-base (sentiment classification).
- **Mixture of Experts**: Combines emotional augmentation with contextual analysis for robust performance.

## Results
- **StanfordNLP/IMDB:** 98% accuracy on binary sentiment classification.
- **US_Airline_Sentiment:** 98% accuracy on multi-class sentiment tasks.
- **StanfordNLP/Sentiment140:** Evaluation in progress.
  
License
This project is licensed under the .

## Contact
For inquiries or collaboration, contact [Hossein.Nekouei@iau.ir] or open an issue on this repository.
