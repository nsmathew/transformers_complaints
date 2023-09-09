# Identifying complaints in social media using deep learning with transformers

> Code for my dissertation @ University of Sheffield, 2022-23.

A complaint is a statement made by a person or an entity with the intent to indicate
something is unacceptable or unsatisfactory. This is commonly used in various aspects of
day-to-day life including when conducting business operations. With the proliferation of
social media and their active enablement by organisations for user engagement, it has become
a common medium for users to raise complaints. With such complaints being publicly visible,
it becomes crucial for organisations to identify, prioritise and respond to these complaints
swiftly. Automatically identifying complaints in social media is an active area of research. In
the past few years, the focus has been on using NLP approaches driven by developments in
transfer learning and transformer-based models.

This paper expands upon using these methods by evaluating different variations of the BERT
model. It includes BERTweet, which is pre-trained using tweets, as well as smaller models,
DistilBERT and BERT Tiny which target to minimize the finetuning and inference time.
Using a publicly available Twitter dataset, BERTweet achieves the highest performance
with an F1 score of 0.908 while the smaller model, DistilBERT exhibits strong predictive
performance for this task. Furthermore, the act of complaining and its nature when used
online and in social media are analysed from a linguistic perspective along with discussions
on state-of-the-art approaches for such NLP tasks.
