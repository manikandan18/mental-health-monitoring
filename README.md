# mental-health-monitoring

In today’s world, there is a need to detect the stress based on various readings from wearable IoT devices in humans and even pets. Stress management has become major topic of discussion and number one reason for heart diseases in humans. 
This project deals the analysis and monitoring of mental health conditions using wearable IoT technology, specifically focusing on cognitive and emotional states. The data was collected from students using wearable sensors such as electroencephalogram (EEG) and galvanic skin response (GSR) sensors.
These sensors monitor brain activity and emotional arousal to detect patterns of stress, anxiety, and cognitive overload. 
Based on this time series data recorded from IoT sensors, the stress levels are classified as high Vs low stress. 
For this project, Mental Health Monitor Using Wearable IoT Sensors data set was used. This dataset was downloaded from Kaggle at https://www.kaggle.com/datasets/ziya07/mental-health-monitor-using-wearable-iot-sensors.


Both LSTM and ESRNN uses deep neural networks that solves the specific problems of time-series data in our project to analyze the stress levels. For this, LSTM was used to predict the stress levels based on the past data. ESRNN was used for training the model for classification of high stress level to low stress level students.
