# NLPHOMEWORK-2
Q1 – Chain Rule of Probability

Explained how the chain rule breaks down sentence probability into a product of conditional probabilities.
Highlighted its use in language modeling for sequence probability estimation.

Conclusion: The chain rule makes complex sequence probabilities computable by splitting them into smaller, manageable conditional terms.

Q2 – Naive Bayes Classification (Confusion Matrix)

Computed per-class precision and recall for Cat, Dog, and Rabbit.
Compared macro vs. micro evaluation metrics to show different perspectives on classifier performance.

Conclusion: Macro treats all classes equally, while Micro emphasizes overall accuracy, showing how evaluation choice changes interpretation.

Q3 – Edit Distance

Worked out minimum edit distance under two different cost models.
Showed how choice of substitution, insertion, and deletion costs changes the alignment outcome.

Conclusion: The edit distance depends heavily on cost settings, highlighting flexibility in modeling real-world spelling or mutation differences.

Q4 – Harms of Classification

Discussed representational harm (stereotype reinforcement).
Identified risks of censorship in toxicity classification (over-blocking identity content).
Explained why dialectal varieties of English face poorer performance due to dataset bias.

Conclusion: Classifier design must address fairness, inclusivity, and social impact to avoid harm in real-world applications.

Q5 – Evaluation Metrics

Analyzed a multi-class confusion matrix.
Reported precision and recall for each class.
Compared macro-averaged vs. micro-averaged metrics and explained interpretation differences.

Conclusion: Macro metrics emphasize balance across classes, while Micro metrics highlight majority-class performance, offering complementary insights.

Q6 – Bigram Probabilities & Zero-Probability Problem

Estimated probabilities for two example sentences using bigram language models.
Showed how zero probabilities arise with unseen words.
Applied smoothing (Add-1) to address the zero-probability issue.

Conclusion: Smoothing ensures unseen events don’t break the model, making language models more robust and realistic.

Q7 – Backoff Model

Calculated trigram probability for a known sequence.
Applied backoff to estimate probability when a trigram was unseen.
Explained why backoff is essential to handle data sparsity.

Conclusion: Backoff balances accuracy and coverage, allowing language models to assign nonzero probabilities even with sparse training data.

Q8 – Programming: Bigram Language Model

Implemented a bigram model in Python.
Counted unigrams and bigrams, and estimated probabilities.
Tested on two sentences, with the model preferring the one more consistent with training data.

Conclusion: Implementation confirmed theoretical bigram calculations, showing that training data strongly influences sentence probability.
