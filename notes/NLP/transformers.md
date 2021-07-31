## Transformers

- [How do Transformers Work in NLP? A Guide to the Latest State-of-the-Art Models](https://medium.com/analytics-vidhya/how-do-transformers-work-in-nlp-a-guide-to-the-latest-state-of-the-art-models-52424082c132)


### BERT
- [Lost in Translation. Found by Transformer. BERT Explained.](https://towardsdatascience.com/lost-in-translation-found-by-transformer-46a16bf6418f)
- [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](http://jalammar.github.io/illustrated-bert/)
- **[How BERT Determines Search Relevance](https://towardsdatascience.com/how-bert-determines-search-relevance-2a67a1575ac4)**
  - *BERT is an acronym for Bidirectional Encoder Representations from Transformers [5], and it’s a language model. A language model encodes words and the log probabilities of words occurring together. The original BERT models did this by being trained on English Wikipedia and the Toronto BookCorpus. The training goals were next sentence prediction, and masked word prediction.*
  - *The masked word task randomly hides a word and rewards BERT for being able to predict the missing word. This task, combined with network dropout, allows BERT to learn to infer a larger context from surrounding words.*
  - *In practice BERT can synthesize a word’s meaning based on the history and understanding of similar neighboring tokens.*
  - *Categorically, emojis are unknown to BERT. Typically, BERT tokenizes emojis as Unknown (literally ‘[UNK]’), and if these aren’t dropped when compressing your page, they don’t add any value when the model sees them*
  - *Fundamentally, since BERT models accept a limited amount of tokens (typically < 505), if your page uses unusual words or uncommon spellings, your page content will be split into more tokens, and in effect, the BERT model will end up seeing less of your page than a similar page that uses more common words and popular spellings.*
  - However, if your search space is smaller, such as just eCommerce technology, or just the products of a home improvement website, etc, then **only a few thousand labeled samples may be necessary** to beat the previous state of the art. Uncommon data is a regular component of search queries:

### ELMO
- [A Step-by-Step NLP Guide to Learn ELMo for Extracting Features from Text](https://medium.com/analytics-vidhya/a-step-by-step-nlp-guide-to-learn-elmo-for-extracting-features-from-text-de0d77e32a99)
- 