# Pitcher-Predictability-Score
Data, Code, Visualizations, and Saberseminar Presentation for Predictability Score

## Synopsis
I ran a recurrent neural network (RNN) on 80% of the pitch sequences in 2025, using the prior pitches in each at bat to predict the next pitch type (fastball, slider, etc.). Then, I introduced the remaining 20% of the data, one pitcher at a time, to get their test accuracy. To be able to compare all of the pitchers on the same plane, I normalized these accuracies using an equation called Normalized Accuracy Gain, which measures the improvement of the model performance from the randomness score (0.25 for a pitcher with 4 pitches in their arsenal) instead of just the model performance. I then compared this score to various other statistics to understand if a pitcher is dangerously predictable or a less-risky predictable.
