## Question and Answers Apps

## Theory

- [BERT NLP — How To Build a Question Answering Bot](https://towardsdatascience.com/bert-nlp-how-to-build-a-question-answering-bot-98b1d1594d7b)
*We can use BERT to extract high-quality language features from the SQuAD text just by adding a single linear layer on top. The linear layer has two outputs, **the first for predicting the probability that the current subtoken is the start of the answer and the second output for the end position of the answer**.*

- [Build a Smart Question Answering System with Fine-Tuned BERT](https://medium.com/saarthi-ai/build-a-smart-question-answering-system-with-fine-tuned-bert-b586e4cfa5f5)
*Note: BERT uses wordpiece tokenization. Wordpiece split the tokens like “playing” to “play and ##ing”. It also covers a wider spectrum of Out-Of-Vocabulary (OOV) words.*

- [How does the [current] best question answering model work?](https://towardsdatascience.com/how-the-current-best-question-answering-model-works-8bbacf375e2a)
  - [Microsoft's R-NET](https://www.microsoft.com/en-us/research/publication/mrc/)
  1. Build representation for the passage and the question separately.
  2. Incorporate the question information into the passage.
  3. Get final representation of the passage by directly matching it against itself.
  4. <u>Predict the start and end position of the answer.</u>

- [Question Answering with PyTorch Transformers: Part 3](https://medium.com/@patonw/question-answering-with-pytorch-transformers-part-3-d67ac06a23b7) - but maybe better to read hugging face docs

- [Deep Learning has (almost) all the answers: Yes/No Question Answering with Transformers](https://medium.com/illuin/deep-learning-has-almost-all-the-answers-yes-no-question-answering-with-transformers-223bebb70189) - Boolean QnA, RoBERTa, ALBERTA, ELECTRA
- **[Hands-on Transformers (Kaggle Google QUEST Q&A Labeling).](https://towardsdatascience.com/hands-on-transformers-kaggle-google-quest-q-a-labeling-affd3dad7bcb)** - One of the better End-to-End (almost) article.



## Refs

## Tools