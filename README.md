# CIFAR-10
• Name: CIFAR-10 (available via keras.datasets) • Classes: 10 object categories (airplane, automobile, bird, etc.)

2 OBJECTIVE
Apply your understanding of CNNs to design and optimize a deep learning model that improves
classification accuracy on the CIFAR-10 dataset. We have already created a basic CNN model
and achieved reasonable accuracy in the online session. Your task is to perform hyper
parameter tuning to improve accuracy to above 80% using simple CNN architectures without
transfer learning.
3 TASKS

3.1 DATA PREPARATION
• Load and normalize the data.
• Apply image augmentation (Optional).
3.2 BASELINE MODEL
• Run the given notebook with a basic CNN model to establish baseline accuracy.
• Evaluate and record test accuracy.
3.3 IMPROVED MODEL
• Experiment with enhancements such as:
o Additional layers (depth/width)
o Batch Normalization
o Dropout
o Optimizer tuning (Adam, SGD with momentum)
o Learning rate scheduler (e.g. ReduceLROnPlateau)
• Add early stopping and checkpoint callbacks.
• Report final test accuracy and compare with baseline.

3.4 EVALUATION
• Plot training and validation accuracy/loss.
• Report confusion matrix and classification report.
• Visualize training curves (accuracy and loss).
4 DELIVERABLES
Submit a Jupyter Notebook containing:
• Complete and readable code with outputs
• Visualizations and model summaries
• Commentary explaining your tuning and design decisions
• Comments on what architectural/ training changes led to improvements and why.
