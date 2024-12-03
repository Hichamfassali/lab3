# Natural Language Processing with Deep Learning: Sequence Models and Transformers

## Objective
The primary goal of this lab is to:
1. Familiarize yourself with PyTorch for building deep neural network architectures.
2. Implement Sequence Models for Natural Language Processing (NLP) tasks, including classification and text generation.
3. Explore advanced architectures such as RNN, GRU, LSTM, and transformers (e.g., GPT-2).

---

## Project Overview
This project is divided into two parts:

### Part 1: Regression Task
#### Work to Do:
1. **Data Collection:**
   - Use web scraping libraries like `Scrapy` or `BeautifulSoup` to collect Arabic text data from several websites based on a specific topic.
   - Format the dataset as follows:

   | Text                  | Score  |
   |-----------------------|--------|
   | Text 1 (Arabic)       | 6.0    |
   | Text 2 (Arabic)       | 7.5    |

   - The `Score` should reflect the relevance of the text to the topic (on a scale from 0 to 10).

2. **Data Preprocessing:**
   - Build an NLP preprocessing pipeline, including:
     - Tokenization
     - Stemming
     - Lemmatization
     - Removing stop words
     - Discretization or normalization
     - Any other necessary preprocessing steps.

3. **Model Training:**
   - Train the collected dataset using the following architectures:
     - Recurrent Neural Networks (RNN)
     - Bidirectional RNN
     - Gated Recurrent Units (GRU)
     - Long Short-Term Memory Networks (LSTM)

   - Perform hyperparameter tuning to achieve the best performance.

4. **Model Evaluation:**
   - Evaluate the trained models using standard metrics .
   - Use advanced metrics like BLEU score to assess performance on the Regression task.

---

### Part 2: Transformer for Text Generation
#### Work to Do:
1. **Setup:**
   - Install the `pytorch-transformers` library.
   - Load the pre-trained GPT-2 model.

2. **Fine-Tuning:**
   - Fine-tune the GPT-2 model on a custom dataset. You can generate the dataset or use a prepared dataset.

3. **Text Generation:**
   - Use the fine-tuned GPT-2 model to generate new paragraphs based on given sentences.

---


