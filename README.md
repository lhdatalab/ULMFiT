# ULMFiT
Classification of airline sentiment twitter text based on ULMFiT - Jeremy Howard et al

### Synopsis
The sentiment data is classified with a confidence level of 80% on average across airlines. For negative sentiment data this drops to 6-70% on average. Th emodel has an overall accuracy of 75% lower than the the overall confidence, hhwoever for negative sentiment the False positive rate (FPR) is
0.045 (negative)
0.56 (positive)
0.63 (neutral)

Hence the confidence level in negative sentiment classification can be said to be around 93%. notebook. This might be especially useful for airlines that have an equal amount of negative, neutral and positive texts, e.g. Southwest and Delta where no one sentiment is overly dominant - see "EDA_ULMFiT_Airline_sentiment_graphs".

Steps to improve overall accuracy includes tuning the neurl network classifier, replacing it with a non-neural network classifier e.g. Support Vector Machine, Modifying vocab by examining misclassification on positive and neutral text.
