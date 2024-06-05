# Evaluating LLMs For Translations
By Jason Tay, Esdras Aleman, Miki Fukushima, Trisha Agrawal

In recent years, commercial large language model (LLM) chatbots have become prevalent, handling various tasks from text summarization to query responses. However, language translation remains a challenging task due to potential discrepancies introduced by ambiguity, context limitations, and nuanced meaning comprehension. This study evaluates the translation capabilities of ChatGPT and Google Gemini using Bible passages as a benchmark, assessing accuracy, fluency, and sentiment. We employed BLEU, METEOR, and cosine similarity with BERT embeddings for accuracy, human annotation for fluency, and VADER and TextBlob for sentiment analysis. Our publicly available dataset of Bible excerpts in English, Spanish, and German reveals that both LLMs perform better with Spanish translations and exhibit some sentiment alterations.

# File Descriptions
**similarity.ipynb**: This notebook consists of the code that calculates BLEU scores, METEOR scores, and cosine similarity between BERT embeddings.

**Sentiment_Metrics.xlsx**: This spreadsheet consists of all data related to sentiment analysis; VADER and TextBlob results and the corresponding visualizations.

**/data/read_and_convert.ipynb**: This notebook contains a Python function that reads in the reference text and converts it to a json file in order to manually enter the LLM outputs prior to analysis.

**/data/excerpt.txt**: This text file contains the reference text with each sentence in English, Spanish, and German. 

**/data/translations_output.json**: This is the final dataset that was used for the analysis in this research.

**/data/output/**: This folder contains folders for each evaluation metric in this research study. Each individual folder has the corresponding scores that were calcuated by the evaluation methods. 

**/data/visualization/**: This folder consists of various visualizations that were created for the Spanish and German translations.

**/data/corpora/**:

**/data/tokenizers/**:
