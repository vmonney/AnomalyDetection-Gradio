# Anomaly Detection in Web Traffic 🚦

This project focuses on detecting anomalies in web traffic across different regions. It's designed to assist IT departments in identifying unusual spikes in data, which could be indicative of security concerns or other issues.

## Overview

The goal is to identify when web traffic hits go above a certain threshold, suggesting potential anomalies. This is achieved through unsupervised anomaly detection techniques.

## Features

- **Data Analysis**: The project includes a comprehensive exploratory data analysis of web traffic data, focusing on identifying patterns and potential anomalies.
- **Machine Learning Models**: Implements models like Isolation Forest, Local Outlier Factor, and OneClass SVM for anomaly detection.
- **Gradio Web Interface**: A user-friendly web interface built with Gradio, allowing users to interact with the model and make predictions.

## Usage

Go to the Gradio web app to start predicting: [Traffic Anomaly Detection 🚦](https://huggingface.co/spaces/vmonney/AnomalyDetectionGradio)

The interface allows you to input traffic data from different regions and get predictions on whether the traffic is normal or anomalous.

## Dataset

The project uses a dataset (`dataset.csv`) containing web traffic data by hosting region over time.

## Model

The Local Outlier Factor model is used for anomaly detection and is saved as `localoutlierfactor.joblib`. This model is loaded in the Gradio app to make predictions.

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository, make changes, and submit a pull request.