# NLP
NLP Project - Fine-tuning of BERT-based model for Emotions and Triggers recognition


The project conducted aims at addressing the Emotion Discovery and Reasoning its Flip in Conversation (EDiReF), SemEval 2024 Task 10, SUBTASK iii (English only).

It consists in classifying Utterances based on Emotions and their Triggers, in multi-people conversations.
We used a BERT-based model, deploting two different settings: 
- Frozen: we froze the BERT embedding layer weights and fine-tuned the classifier heads on top,
- Unfrozen (or Full): we fine-tuned the whole model architecture.

The results obtained are promising, and wink at future improvements.
