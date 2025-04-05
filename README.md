# Sentiment Analysis with Emotional Augmentation

## Overview
This repository contains an innovative approach to sentiment analysis that enhances accuracy by integrating emotional context into text data. By combining a text-to-text generation model (Flan-T5-large) with a contextual sentiment analysis model (RoBERTa-base), this project achieves a state-of-the-art accuracy of  _**98%**_ on sentiment classification tasks. The methodology leverages a mixture-of-experts structure to improve the understanding of sentence-level sentiment.

## Methodology
The proposed approach consists of two main stages:

## Emotional Augmentation:
A text-to-text generation model, **_Flan-T5-large_**, is used to enrich original tweets or sentences by adding key emotional aspects. This step enhances the emotional context of the input text, making it more expressive and informative.
Sentiment Analysis:
The augmented text is then fed into **_RoBERTa-base_**, a contextual model fine-tuned for sentiment classification. This model analyzes the enriched text to predict sentiment with higher precision.
This hybrid structure effectively combines generative and discriminative techniques, resulting in superior performance compared to traditional sentiment analysis methods.

## Datasets
**Tested Datasets:**
**StanfordNLP/IMDB:** Movie reviews dataset for binary sentiment classification.
**US_Airline_Sentiment:** Twitter data on airline experiences for multi-class sentiment analysis.

**Planned Dataset:**
**StanfordNLP/Sentiment140:** Large-scale Twitter dataset for sentiment analysis (work in progress).

## Key Features
Accuracy: Achieves an overall accuracy of **_98%_** on sentiment classification.

## Models Used:
Flan-T5-large for text augmentation.
RoBERTa-base for sentiment analysis.

## Mixture of Experts: 
Integrates emotional augmentation and contextual analysis for robust sentiment detection.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or bugs.

## License
This project is licensed under the MIT License

## Contact
For questions or collaboration, feel free to reach out via [Hossein.Nekouei@iau.ir] or open an issue on this repository.
