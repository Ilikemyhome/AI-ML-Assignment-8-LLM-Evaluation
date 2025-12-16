# AI-ML-Assignment-8-LLM-Evaluation

##  Demo: Sentiment Classification

After fine-tuning DistilBERT with LoRA on the IMDB dataset, the model can classify raw text reviews into **Positive** or **Negative** sentiment.

### Example 1: Clear Positive
```python
text1 = "This movie was fantastic, I loved it!"
print(sentiment_pipeline(text1))

[{'label': 'POSITIVE', 'score': 0.96}]

### Example 2:Ambiguous / Mixed Sentiment
text2 = "The movie had great visuals but the story was boring."
print(sentiment_pipeline(text2))

[{'label': 'NEGATIVE', 'score': 0.80}]

```
- LABEL_0 = Negative
- LABEL_1 = Positive
