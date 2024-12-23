# Debugging-Assignment
Debugging exercises for Python and deep learning, covering data structures, visualization with Matplotlib, and GANs using PyTorch. Real-world scenarios with detailed problem statements and expected outcomes to enhance practical debugging skills. Suitable for beginners to advanced learners.
# Mind Map: Data Pre-Processing Workflow

```mermaid
mindmap
  root((Data Pre-Processing))
    Data Cleaning
      Handle Missing Values
        Replace with Mean
      Remove Outliers
        Interquartile Range (IQR) Method
      Remove Duplicates
      Final Clean Data
    Feature Scaling
      Min-Max Normalization
        For SVM, KNN
      Standardization
        For Logistic Regression
    Feature Selection
      Correlation Matrix
        Eliminate Highly Correlated Features
      Recursive Feature Elimination (RFE)
        Retain Most Relevant Features
    Data Augmentation
      Noise Injection
      Time Shifting
      Frequency Shifting
      Signal Stretching/Compression
    Dataset Splitting
      Training Set (80%)
      Test Set (20%)
      Z-Score Normalization
        For Deep Learning Models
