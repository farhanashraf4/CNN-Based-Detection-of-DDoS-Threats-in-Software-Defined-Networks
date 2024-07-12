# CNN-Based-Detection-of-DDoS-Threats-in-Software-Defined-Networks

## Objective

The aim of this project is to develop a robust DDoS attack detection system tailored for Software-Defined Networking (SDN) environments using advanced machine learning and deep learning techniques to enhance network security.

## Preprocessing

The following preprocessing steps are applied to the datasets:

1. **Handling Missing Values**: Impute or remove missing values as necessary.
2. **Encoding Categorical Features**: Convert categorical features to numerical representations using techniques like one-hot encoding.
3. **Scaling Numerical Features**: Normalize or standardize numerical features for improved model performance.
4. **Addressing Class Imbalance**: Use the `RandomOverSampler` technique to balance the classes and ensure the model is not biased towards the majority class.

## Model Development

We implement and train a Convolutional Neural Network (CNN) model optimized for traffic feature analysis. The key aspects of model development include:

1. **Frameworks Used**: TensorFlow and Keras for CNN model development.
2. **Data Preprocessing**: Using scikit-learn for preprocessing tasks.
3. **Training**:
   - **Early Stopping**: To prevent overfitting by stopping the training process when the performance on a validation dataset starts to degrade.
   - **Learning Rate Reduction**: To fine-tune the learning rate during training for better convergence.

## Evaluation

To ensure accurate detection of DDoS and other attack types, we evaluate the model's performance using the following metrics:

1. **Confusion Matrix**: To visualize true positive, true negative, false positive, and false negative predictions.
2. **ROC Curve**: To evaluate the model's ability to distinguish between classes.
3. **Precision-Recall Curve**: To assess the trade-off between precision and recall.
4. **Matthews Correlation Coefficient**: To provide a balanced measure of the model's performance, especially with imbalanced classes.
5. **Classification Reports**: To present precision, recall, F1-score, and support for each class.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ddos-detection-sdn.git
   cd ddos-detection-sdn
