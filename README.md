# Document binary classification (signed or not)
The dataset contains information relative to different documents. The goal is to develop a predictive model to decide whether a document will be signed or not.

The metrics chosen were accuracy but as the customer commented that "to us predicting that a document will be signed when in reality it won’t is slightly worse than otherwise (predicting a document to not be signed when it is in fact signed)." we have to pay attention to minimize the False Positives increasing the precission playing with the threshold feature of sklearn.
