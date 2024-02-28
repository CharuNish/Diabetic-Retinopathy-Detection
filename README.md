# Diabetic-Retinopathy-Detection

## Overview
Diabetic Retinopathy (DR) is the leading cause of blindness in the working-age population of the developed world, affecting an estimated 93 million people globally. The US Center for Disease Control and Prevention reports that 29.1 million Americans have diabetes, while the World Health Organization estimates a worldwide prevalence of 347 million people. Approximately 40% to 45% of Americans with diabetes exhibit some stage of DR, a disease that can progress to vision impairment but can be managed if detected early. However, early detection is challenging due to the often asymptomatic nature of the disease until it advances to a critical stage.

## Problem Statement
Currently, DR detection is a manual, time-consuming process that relies on the expertise of trained clinicians to examine digital color fundus photographs of the retina. This method is not only slow—often taking days for results—but also prone to delays and miscommunication, leading to postponed treatment. Furthermore, the expertise and equipment required for accurate DR diagnosis are scarce in regions with high diabetes prevalence, where DR detection is crucial.

## Solution
To address these challenges, we propose a deep learning model based on Convolutional Neural Networks (CNNs) and Residual Blocks designed to automatically detect the presence and type of Diabetic Retinopathy from high-resolution retina images. Our model aims to classify the severity of DR on a scale from 0 to 4, as follows:

- 0: No DR
- 1: Mild
- 2: Moderate
- 3: Severe
- 4: Proliferative DR

## Achievements
This model has achieved an accuracy of 83.1%, demonstrating its potential to significantly expedite the DR detection process, reduce the demand on clinician time and resources, and ultimately facilitate earlier treatment interventions.

## Dataset
The dataset consists of a large set of high-resolution retina images, each labeled with an ID and a clinician's diagnosis according to the severity scale mentioned above. 

