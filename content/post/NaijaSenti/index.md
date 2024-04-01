---
title: NaijaSenti Dataset
subtitle: Writing technical content in Markdown
date: 2024-01-04
math: true
draft: false
---

In the rapidly evolving field of Natural Language Processing (NLP), sentiment analysis stands out as a crucial application, enabling machines to understand human emotions expressed in text. Despite its significance, the majority of sentiment analysis research has been concentrated on languages with abundant resources, such as English, leaving languages with limited data underrepresented. This gap is particularly evident in the context of Nigeria, Africa's most populous country, which boasts over 522 native languages. Recognizing this disparity, our research introduces "NaijaSenti," the first large-scale, human-annotated Twitter sentiment dataset for the four most widely spoken Nigerian languages: Hausa, Igbo, Nigerian-Pidgin, and Yorùbá. This dataset, comprising around 30,000 annotated tweets per language, including a significant fraction of code-mixed tweets, aims to bridge the gap in sentiment analysis for these underrepresented languages.

## Tweet Collection

To compile the NaijaSenti dataset, we employed a comprehensive methodology encompassing text collection, filtering, processing, and labeling tailored to the unique challenges of low-resource languages. Given the absence of API support for Nigerian languages, we devised heuristic approaches for tweet collection, leveraging stopwords, emojis, and sentiment words for initial filtering. Subsequently, tweets were manually annotated based on a detailed guideline that classified them into five sentiment categories: positive, negative, neutral, mixed, and indeterminate. This process involved rigorous training and iteration among annotators to ensure consistency and accuracy. Additionally, we created sentiment lexicons for Hausa, Igbo, and Yorùbá by tagging words conveying sentiments within tweets, further enriching our dataset's utility for sentiment analysis.

## Results

Our extensive experiments with pre-trained models and transfer learning strategies on the NaijaSenti dataset revealed insightful findings. Language-specific models and language-adaptive fine-tuning emerged as the most effective approaches, with AfriBERTa, a model trained on African languages, showing superior performance across all four languages. The dataset also highlighted the prevalence of code-mixing and the challenges posed by the absence of diacritics in languages like Yorùbá and Igbo. Furthermore, our analysis of inter-annotator agreement underscored the complexity of sentiment annotation, particularly for tweets with mixed sentiments. The human evaluation of the dataset confirmed its reliability, setting a benchmark for future research in sentiment analysis for Nigerian languages.

## Conclusion

NaijaSenti represents a significant stride towards inclusivity in NLP research, offering the largest labeled sentiment dataset for Hausa, Igbo, Nigerian-Pidgin, and Yorùbá to date. By making this dataset, along with trained models, sentiment lexicons, and code, freely available, we aim to stimulate further research and development in sentiment analysis for underrepresented languages. Our findings underscore the potential of language-specific models and adaptive fine-tuning in enhancing sentiment analysis performance. We plan to extend NaijaSenti to encompass other African languages, broadening the scope of sentiment analysis research across the continent.

<style>
body {
text-align: justify}
</style>