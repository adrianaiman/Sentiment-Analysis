##  Future Work

To further improve the performance and interpretability of the sentiment analysis pipeline, the following future directions are proposed:

### 1. Address Class Imbalance
-  Implement oversampling techniques such as **SMOTE** or apply **undersampling** to balance the training set.
-  Experiment with **cost-sensitive learning** or use **class-weighted loss functions** in deep learning models to better handle underrepresented sentiment classes.

### 2. Ensemble Learning
-  Combine multiple traditional classifiers using **voting** or **stacking** techniques.
-  Improve robustness, especially in classifying difficult cases such as **neutral reviews**, by leveraging ensemble predictions.

### 3. Advanced Aspect-Based Sentiment Analysis (ABSA)
-  Move beyond basic noun-phrase extraction (e.g., TextBlob) by incorporating:
  - **Dependency parsing** for more accurate aspect extraction.
  - **Transformer-based ABSA models** like **BERT-PT** or **SpanBERT** to capture richer contextual sentiment.

By exploring these improvements, the system can evolve into a more **scalable**, **fair**, and **explainable** framework—suitable for real-world applications in **app review analysis** and **user feedback systems**.
