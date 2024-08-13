In this project, we investigate different approaches to training deep learning models for medical imaging recognition Our task involves conducting experiments on two medical imaging
datasets, specifically in BreastMNIST. We aim to explore modern techniques in the
problem of image classification. Despite employing a supervised approach, imbalanced data can still pose
challenges, where a dataset may have a disproportionate number of members in a specific class compared
to another. LibAUC provides a deep learning library that directly optimizes commonly used performance
metrics. In our case, we work on maximizing the ROC curve (Receiver Operating Characteristic curve),
which illustrates the performance of a classification model and provides an aggregate measure of performance across all possible classification thresholds. Our focus must now shift to optimizing LibAUC’s
AUCM loss metric. Thus, after using the ResNet18 architecture, we experiment with various models and learning
techniques to demonstrate their effectiveness.
