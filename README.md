# Project Title: Aspect-Based-Sentiment-Analysis-Peer-Reviews-Paper-Acceptance

# Project Description: 

This project utilizes ICLR papers from 2017-2020 and NIPS papers from 2016-2019, along with their associated reviews, to explore how aspect-based sentiment analysis can predict paper acceptance or rejection. While sentiment analysis has been applied to predict paper outcomes based on reviews, this project specifically focuses on the relationships between detailed aspects of peer reviews (such as clarity, soundness, originality, and motivation) and paper acceptance.

The project aims to answer two main research questions:

- Can aspect-based sentiment analysis improve paper acceptance prediction by leveraging detailed aspects of peer reviews?

- How does fine-tuning a transformer-based model, like BERT, enhance the understanding of aspects in peer reviews for more accurate paper acceptance predictions?

To address these questions, a BERT model fine-tuned on peer review data will be used in conjunction with a Multi-Layer Perceptron (MLP) for final classification. The model’s performance will be evaluated using accuracy and F1-score metrics, with the goal of providing clearer interpretations of peer feedback to assist researchers in the decision-making process.
