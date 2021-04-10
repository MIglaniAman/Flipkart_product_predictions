# Flipkart_product_predictions
+------+--------------------------+-------------------------+-----------------------------+---------+--------------+
| S.no |          Model           |          Method         |     Best Hyperparameter     | f1score | Hamming_loss |
+------+--------------------------+-------------------------+-----------------------------+---------+--------------+
|  1   | Logistic Regression (L2) |       Bag of Words      |       {0.1, 'alpha ='}      |  0.9341 |   0.06671    |
|  2   | Logistic Regression(L1)  |       Bag of Words      |     {0.0001, 'alpha ='}     |  0.916  |   0.08887    |
|  3   | Logistic Regression (L2) |          TFIDF          |     {0.0001, 'alpha ='}     |  0.9691 |   0.02908    |
|  4   | Logistic Regression (L2) | TFIDF weighted word2vec |     {0.0001, 'alpha ='}     |  0.9164 |   0.08358    |
|  5   |    Random Forest(RF)     |       Bag of Words      |  {'n_es': 80, 'max_d': 500} |  0.9573 |   0.04271    |
|  6   |    Random Forest(RF)     |          TFIDF          | {'max_d': None, 'n_es': 60} |  0.9342 |   0.06589    |
|  7   |    Random Forest(RF)     | TFIDF weighted word2vec | {'max_d': 100, 'n_es': 200} |  0.9431 |   0.05694    |
+------+--------------------------+-------------------------+-----------------------------+---------+--------------+
