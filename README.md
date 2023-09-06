# Comparison of different Neural Net architectures on Sentiment Analysis task
## Motivation
Sentiment analysis plays a crucial role in understanding public opinion, customer feedback, and social trends, the motivation for our project was twofold
Exploration: We wanted to explore the strengths and weaknesses of different neural network architectures, including the powerful pre-trained BERT model, traditional LSTM, and CNN models. This exploration allows us to gain insights into their applicability in sentiment analysis tasks.
Performance Evaluation: By rigorously evaluating these models using metrics like the Matthews Correlation Coefficient (MCC) and the F1 score, we aimed to provide a comprehensive performance assessment.
Our aim was to assess and compare their performance in the context of sentiment analysis.
## Model Development
### BERT-Based Model
We harnessed the power of pre-trained BERT for Sequence Classification, capitalizing on its ability to understand and classify sequences of text. Before inputting data into the BERT model, we conducted text pre-processing and tokenization to ensure it was ready for analysis.
### LSTM and CNN Models
We also constructed separate LSTM and CNN models. For these models, we executed text pre-processing and tokenization, followed by the use of pre-trained GloVe word embeddings to encode text as input. These models were designed to capture different aspects of textual information.
## Performance Evaluation
Our primary focus was on evaluating model performance. We used metrics such as the Matthews Correlation Coefficient (MCC) and the F1 score to assess how well each model classified sentiment.
## Results
The pre-trained BERT model outperformed the LSTM and CNN models. It achieved a higher Matthews Correlation Coefficient (MCC) score of approximately 0.81, indicating its robustness in handling imbalanced sentiment data. Moreover, the BERT model demonstrated a significantly higher F1 score, around 0.90, showcasing its precision and ability to effectively identify sentiment nuances.
This project underscores the supremacy of the pre-trained BERT model in the domain of sentiment analysis, illustrating its capacity to surpass traditional neural network architectures like LSTM and CNN. It highlights the importance of choosing the right model for specific natural language processing tasks and sets a benchmark for future sentiment analysis endeavors.
