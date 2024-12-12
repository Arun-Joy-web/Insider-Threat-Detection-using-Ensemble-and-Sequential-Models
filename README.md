# Insider Threat Detection using Ensemble and Sequential Models

## Overview

This project analyzes email activity data to identify anomalies and predict anomalous behavior using a variety of machine learning models, including tree-based methods and deep learning architectures.

The pipeline includes data preprocessing, feature engineering, exploratory data analysis (EDA) and the application of advanced classification techniques to detect anomalies in email usage patterns.

---

## Features

1. **Data Analysis**:
   - Visualization of email activity patterns.
   - Exploration of user activity and attachments.

2. **Feature Engineering**:
   - Extraction of features such as number of recipients, hour of day and day of the week.
   - Use of TF-IDF for email content vectorization.

3. **Anomaly Detection**:
   - Implementation of Isolation Forest for unsupervised anomaly detection.

4. **Classification Models**:
   - Random Forest
   - Gradient Boosting
   - Multi-Layer Perceptron (MLP)
   - Stacking Ensemble
   - LSTM (Long Short-Term Memory)
   - GRU (Gated Recurrent Unit)

5. **Performance Metrics**:
   - Accuracy
   - Classification reports (precision, recall, F1-score)

---

## Requirements

To run this project, the following libraries are required:

- Python 3.10.12
- pandas 2.2.2
- numpy 1.26.4
- scikit-learn 1.5.2
- TensorFlow/Keras 2.17.1
- matplotlib 3.8.0
- seaborn 0.13.2

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

---

## Data

The project uses an `email.csv` file containing the following columns:
- **date**: Timestamp of the email.
- **user**: Sender of the email.
- **to, cc, bcc**: Recipients of the email.
- **attachments**: Number of attachments.
- **content**: Text content of the email.

Ensure the dataset is placed in the project directory.

---

## Usage

1. **Load the Data**:
   Modify the script to ensure the correct path to `email.csv`.

2. **Run the Script**:
   Execute the Python script to perform analysis, anomaly detection, and classification:
   ```bash
   python projectcode.py
   ```

3. **Model Outputs**:
   - Anomaly detection results are added as a new column to the dataset.
   - Model performance metrics are printed in the console.

---

## Key Results

- **Visualization**:
  - Email activity trends by hour and user.
- **Anomaly Detection**:
  - Identification of unusual email behaviors using Isolation Forest.
- **Classification Accuracy**:
  - Random Forest: 99.112 %
  - LSTM: 98.669 %
  - GRU: 98.649 %
  - Gradient Boosting: 98.456 %
  - Multi-Layer Perceptron (MLP): 98.939 %
  - Stacking Ensemble: 99.112 %

---

## Customization

- Adjust contamination levels in the Isolation Forest to fine-tune anomaly sensitivity.
- Modify TF-IDF vectorization settings for different textual datasets.
- Experiment with hyperparameters in the provided classification models.

---

## License

This project is licensed under the MIT License.

---

## Contact

For any questions or issues, please contact Arun Joy at arunjoy2002@gmail.com.

--- 

##GitHub URL

https://github.com/Arun-Joy-web/Insider-Threat-Detection-using-Ensemble-and-Sequential-Models/blob/main/

