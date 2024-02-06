# Detecting Mild Cognitive Impairment (MCI) Behavioral Anomalies in Smart Home Environments

## Context
Mild Cognitive Impairment (MCI) is a critical stage between normal aging and dementia, where early detection of behavioral anomalies offers intervention opportunities. MCI can be further classified into two distinct subtypes: amnestic and non-amnestic MCI. In amnestic MCI (aMCI), memory loss is a mainstay symptom whereby the affected individual has a higher frequency of forgetting things compared to usual. On the other hand, non-amnestic MCI (naMCI) does not display significant memory loss, but other cognitive domains such as language and attention are impaired. 

This dissertation explores the use of machine learning to detect MCI-related behavioural anomalies within smart home environments.

## Objectives
The study aims to:
- Develop a methodology to simulate MCI-related behavioral anomalies.
- Apply HMM to detect these anomalies.
- Evaluate HMM’s anomaly detection capabilities against state-of-the-art methods.

## Dataset
- The dataset used in this study is called 'Aruba' and was obtained from the Center for Advanced Studies in Adaptive Systems (CASAS) - https://casas.wsu.edu/datasets/
- The Aruba dataset consists 220 days of continuous data (no missing days) with 11 activities annotated
- Thirty-nine sensors, including thirty-four passive infrared sensors and five temperature sensors were used during data collection in a home of an elderly woman. 

## Methods
- Data preprocessing (data cleansing, transformation, partitioning)
- Synthesis of abnormal activities associated with MCI subtypes (amnestic MCI and non-amnestic MCI)
- HMM was chosen as the primary anomaly detection method and compared with Long Short-Term Memory (LSTM) and Gated Recurrent Unit Autoencoders (GRU-AE) using various metrics

## Results
- Simulated anomalies effectively replicated common MCI-related behavioral patterns.
- HMM consistently outperformed LSTM and GRU-AE in detecting anomalies across all metrics. Statistical analysis confirmed significant differences favoring HMM, demonstrating its effectiveness and consistency in identifying MCI-related anomalies.
- HMM showcased a slightly more pronounced effectiveness in detecting anomalies within the aMCI subtype.

## Discussion
- This research has implications in social care and neurology, facilitating early disease interventions.
- While the anomaly simulation method successfully introduced MCI-related anomalies, there remains bias in the simulated dataset due to the variability in behavior among MCI individuals.
- Further analysis beyond activity patterns, such as activity duration, could enhance anomaly detection.
- Future research could explore online learning techniques to adapt to changing habits.
