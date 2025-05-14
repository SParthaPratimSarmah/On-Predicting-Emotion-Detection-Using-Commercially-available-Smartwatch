<h1> Publications: On Predicting Emotion From Commercial Smartwatch - A Big Data Narrative</h1>
<strong>Authors:</strong> Partha Pratim Sarmah; Partha Sarathi Paul; Krishnandu Hazra
Read this: https://ieeexplore.ieee.org/document/10984709
<h4>About:</h4>
<p>
Smart wearable devices such as smartwatches and smart bands are all-pervasive nowadays. They are accompanied by various sensors like heart rate monitors, oximetry sensors, ambient light and temperature sensors, etc. that collect different physiological data about the individuals while wearing. Such data can effectively be used to detect the activities of the user. Here, one relevant intriguing question arises: Is it feasible to predict the emotional status of an individual by utilizing such physiological data from such devices? To address this question, no such work utilizes commercial smartwatches. Therefore, to fill this gap, in this work, we analyze and predict emotions by utilizing the physiological data collected by the commercial Fitbit smartwatch. Here, we have utilized the Lifesnaps Fitbit dataset, a large public dataset of size 9.72 GB that contains both physiological sensor data and psychological survey data collected from 71 volunteers from different demographic areas using commercially available Fitbit smartwatches between May 2021 and January 2022. Here we investigate the correlation between emotional state and physiological parameters using data collected from the Lifesnaps dataset. We perform comprehensive data pre-processing such as data cleaning, data imputation, and scaling to ensure the data integration and usability of the dataset. We apply various non-neural machine learning algorithms (Support Vector Machine, Logistic Regression, Decision Trees, LightGBM, XGBoost, and Random Forest) and achieve an accuracy of up to 78.75% in predicting emotions. We further enhanced the performance of the prediction through efficiently hyper-tuning two neural network approaches (i.e., Feedforward neural network, and BiLSTM) and achieved a maximum accuracy of 97% in the Feedforward neural network. Our experimental evaluation shows a significant potential in commercial smartwatches for mental health and emotion detection.</p>


<h1>Emotion Prediction Using Commercial Smartwatches</h1>
 In the 21st century, smart wearable devices such as smartwatches, smart bands, etc., are widespread;
 nearly 224 million people use smartwatches worldwide in 2024, and this number will reach up
 to 228 million by 2026. Such popularity is due to their technological advancements and numerous exciting features, such as health monitoring, activity tracking, fitness tracking, GPS, and
 others. Apart from the basic utility, such devices are enriched with different sensors, such as
 Heat Rate Monitors, Oximetry Sensors, Accelerometers, Gyroscopes, and others. Such sensors
 can capture various physiological and activity-related user data while wearing.
 Such wearable devices can be utilized to predict the emotional state of an individual. Detecting
an emotional state is crucial for understanding the well-being of an individual, as it is associated
 with the quality of their life. One of the early signs of a mental disorder is the bad emotional
 state of a person for a long time. Furthermore, in certain professions, such as aviation
 and transportation, an individual’s emotional condition can directly impact public safety; thus,
 monitoring emotions becomes particularly important. Consequently, there is a growing need
 for emotion recognition systems capable of accurately detecting emotions in real time. In recent
 years, numerous studies have explored the potential of wearable devices and sensor-dense setups
 for predicting emotional states.

  In this work, we analyze and predict emotional states using various physiological data
collected from commercial smartwatches. Here, we have utilized the Lifesnaps public dataset,
 which contains both physiological sensor data and psychological survey data collected from 71
 volunteers from different demographic areas using commercially available Fitbit Sense smartwatches between May 2021 and January 2022. We used 
 study between the physiological data and self-reported emotional states to establish the
 feasibility of the current research. From the correlation, we found that bpm, resting hr, fil
teredDemographicVO2Max and calories show a higher correlation with emotions. We adjusted
 the weight according to the correlation strength. We applied six different non-neural machine
 learning algorithms (SVM, LR, DT, LightGBM, XGBoost, and RF) and achieved the highest
 accuracy of 78.75%. Next, we applied the neural network-based method to predict the emotions
 and get the highest accuracy of 97%. So, our work shows a strong potential for commercially
 available smartwatches to be utilized for emotion detection and mental health monitoring.
![Alt text](BILSTMVSFEED.png)
![Alt text](AccuracyIncreasesIndifferentModel.png)
