# Text_summarization
Text Summarization using Extractive approach. <br>

The extractive approach to text summarization aims to create a summary by selecting and extracting sentences directly from the source document. This method involves the following steps:

### Scoring Sentences: 
Sentences within the document are scored based on various criteria, such as length, keyword importance, or advanced algorithms like PageRank. This scoring determines the significance of each sentence.

### Sentence Selection: 
Sentences with the highest scores are chosen for inclusion in the summary. These sentences represent the most crucial parts of the document.

### Assembling the Summary: 
The selected sentences are organized to create a coherent summary. Despite being extracted from different parts of the document, they are arranged to ensure readability and logical flow.

### Condensed Version: 
The final output is a shortened version of the source document, offering an overview of its main points and key information.

### NLP Enhancement: 
Natural Language Processing (NLP) techniques are often applied to improve sentence scoring accuracy and ensure cohesiveness in the summary.


## GloVe Embedding: 
The GloVe model, short for "Global Vectors for Word Representation," is an unsupervised machine learning algorithm used in natural language processing (NLP) to learn vector representations (word embeddings) of words in a large corpus of text. GloVe combines elements of both global and local context in its word representations. Global context refers to the relationships between words that occur throughout a large corpus of text. For example, it captures the fact that "king" is related to "queen" and "man" is related to "woman". Local context considers the co-occurrence of words within a fixed-size window around a target word.

### Co-Occurrence Matrix:
The foundation of GloVe is a co-occurrence matrix that captures how often words co-occur within a given context. Each cell in the matrix represents the number of times two words occur together in a context window.
