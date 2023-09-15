# Thermal-Comfort-Modeling: What is this project?

Thermal comfort is an important component of the built environment and affects the health and well-being of occupants. Personal comfort models (PCMs) are a novel paradigm in thermal comfort 
modeling and they use sensor data with machine learning algorithms. This project explores the use of deep learning for developing PCMs of 14 occupants using their raw physiological signals. 
We argue that deep learning approaches can better learn the temporal features of the time series data. Results show that deep learning can help in improving the overall performance of PCMs.

# What dataset was used ?

The dataset used in this project uses raw physiological signals (skin temperature, heart rate, and accelerometer) of 14 occupants (6 female and 8 male adults) and environmental parameters (air temperature and relative humidity) for 2–4 weeks. The label used for classification is the occupant’s thermal preference (cooler, no change, warmer).

# Methodology

This project uses three deep learning approaches, namely Fully Convolutional Network (FCN), Multi-scale Convolutional Neural Network (MCNN), and Multi-Channel Deep Convolutional Neural Network (MCDCNN) for time series classification of thermal preference based on the physiological signals of 14 occupants. We compare the accuracy of these approaches with traditional machine learning ensemble tree classifiers. Results show that deep learning time series classification approaches can perform at par with machine learning classifiers without the need for feature engineering.
