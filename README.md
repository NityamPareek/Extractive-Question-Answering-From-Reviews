# Extractive-Question-Answering-From-Reviews

# Objective
The objective here is to extract answers related to a product from its multiple reviews online. This comes under the category of extractive question-answering.

# Methodology
1. Decided to choose a transformer fine-tuned on the SQuAD dataset because the training set is relatively small, consisting of <1500 examples.
2. Went ahead with the MiniLM transformer as it is fast, accurate, and lightweight.
3. Initialised a retriever-reader architecture to eliminate the need to give a context.
4. Used the ElasticSearch document store.
5. Currently experimenting with both sparse and dense retrievers, and comparing their performance. Looking at metrics such as Top-k recall.
6. Learning about domain adaptation and its impact on overall performance.

# To Do Ahead
1. Deploy the pipelines.
2. Learn about methods to improve the performance of the overall pipeline.
3. Experiment with Generative Question Answering.
