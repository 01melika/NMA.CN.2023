## Understanding Brain Signals: A Computer's Perspective

**Imagine your brain is a busy city.** There are many different areas, each with its own role. This project is like trying to understand what’s happening in this city by listening to the conversations of the people (neurons) who live there.

We want to see if we can use computers to figure out what a person is seeing or doing based on the brain signals.The project employed computational methods to investigate the relationship between neural activity and sensory processing. Specifically, it aimed to decode sensory stimuli, in this case, visual contrast levels, from neural population recordings.


**What we did:**
Data Acquisition: Neural data was obtained from a large-scale dataset containing multi-unit recordings from various brain regions of mice performing a visual discrimination task.
Data Preprocessing: Neural data was aligned to stimulus onset, and specific brain regions (visual cortex) were isolated for analysis. To address class imbalance in the contrast levels, undersampling techniques were applied.
Feature Extraction: Time-series neural data was converted into static features through averaging within specific time windows.
Model Development: Support Vector Machines (SVMs) were employed as the classification model to predict contrast levels based on the extracted neural features. Model performance was evaluated using accuracy metrics.
Model Refinement: Grid search was implemented to optimize SVM hyperparameters, and the impact of different time window lengths on prediction accuracy was explored.
Correlation Analysis: Mutual information was calculated to assess the relationship between neural activity and stimulus contrast.

**What we found:**
Preliminary results suggest a correlation between neural activity in the visual cortex and stimulus contrast levels. The SVM models achieved above-chance performance in predicting contrast levels, demonstrating the potential of decoding sensory information from neural populations. However, the accuracy of these predictions varied across different time windows, indicating the dynamic nature of neural representations.


**Think of it like teaching a robot to understand human language by listening to lots of conversations.** 
