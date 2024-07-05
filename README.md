<h1 align='center'>Network Intrusion Detection</h1>
<h3 align='center'>Orestas Dulinskas</h3>
<h4 align='center'>July 2024</h4>

<h5 align='center'>https://www.kaggle.com/code/orestasdulinskas/network-intrusion-detection</h5>

## Background

In today's interconnected digital world, network security is a paramount concern for organizations and individuals alike. With the increasing sophistication and frequency of cyber attacks, traditional intrusion detection systems often struggle to keep up. This has led to a growing interest in leveraging advanced machine learning techniques to enhance the detection and prevention of malicious network activities. One promising approach is the use of artificial neural networks (ANNs) to analyze network flow data and identify potential intrusions. This project aims to utilize the LUFlow dataset, a comprehensive and continuously updated repository of network telemetry, to develop a neural network model capable of detecting malicious network intrusions effectively.

## Objective

The primary objective of this project is to develop and train an artificial neural network (ANN) model to detect malicious network intrusions using the LUFlow dataset. The specific goals include:
1. Creating a robust ANN model that can accurately distinguish between benign, malicious and outlier network traffic.
2. Enhancing the overall effectiveness and responsiveness of network intrusion detection systems by integrating advanced machine learning techniques.

## Data

The LUFlow dataset is a flow-based network intrusion detection dataset that provides a rich ground truth for malicious behavior through the correlation of telemetry data with third-party Cyber Threat Intelligence (CTI) sources. This dataset includes various types of network traffic, captured from Lancaster University's address space, and is designed to promote research into detection mechanisms for emerging threats.

Key features of the LUFlow dataset include:
- **Comprehensive Coverage:** The dataset contains telemetry data from both normal and malicious network activities, including traffic from production services such as SSH and database traffic.
- **Robust Ground Truth:** The labelling mechanism is autonomous and supported by a robust ground truth, enabling constant capture, labelling, and publishing of telemetry data.
- **Outlier Detection:** Flows that cannot be determined as malicious but do not conform to normal traffic profiles are labeled as outliers, encouraging further analysis to understand their intent.
- **Continuous Updates:** The dataset is continuously updated to reflect novel and emerging attack patterns, ensuring that the detection mechanisms developed using this data remain relevant and effective.

For this project, the dataset from September 2020 will be used, comprising over 26 million rows and 15 columns, with a total memory size of over 3.3GB. This extensive dataset provides a rich source of information for training the ANN model, enabling it to learn the subtle distinctions between normal and malicious network traffic and to adapt to evolving threats.
