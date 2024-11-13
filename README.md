## EARLY-DETECTION-OF-CHRONIC-KIDNEY-DISEASE

The primary goal of this project is to develop a robust and efficient deep learning model to assist in the automated classification of kidney abnormalities.


## About
<!--Detailed Description about the project-->
This project focuses on classifying kidney CT scan images into four distinct categories: Normal, Cyst, Tumor, and Stone using a deep learning model based on the VGG16 architecture. By leveraging transfer learning from the pre-trained VGG16 model, we aim to enhance feature extraction from the images and improve the model's classification accuracy.The dataset used in this project comprises CT images categorized into the four aforementioned classes. The model is trained using TensorFlow and Keras, with careful data preprocessing and augmentation to ensure high accuracy and generalization on unseen data.

## Features
<!--List the features of the project as shown below-->

  * Accurate Kidney Classification
  
  * Efficient Image Preprocessing

  * High scalability.

  * Comprehensive Performance Metrics
  
  * Real-time Prediction

## Requirements
<!--List the requirements of the project as shown below-->

  
  * Operating System: Requires a 64-bit OS (Windows 10/11 or Ubuntu) to ensure compatibility with deep learning frameworks.
  
  * Development Environment: Python 3.7 or later is necessary for implementing and training the kidney classification model.
    
  * Deep Learning Frameworks: TensorFlow for building and training the VGG16-based neural network model.
  
  * Image Processing Libraries: OpenCV for efficient image preprocessing and visualization of kidney CT scans.
  
  * Version Control: Git for collaborative development and version tracking of the project’s codebase.
  
  * IDE: Use of Visual Studio Code (VSCode) as the Integrated Development Environment for code writing, debugging, and version control.
  
  * Additional Dependencies: Includes TensorFlow, Keras, scikit-learn, OpenCV, and Matplotlib for data processing, model training, and performance visualization tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2024-11-11 213405](https://github.com/user-attachments/assets/9d25c6ca-7edc-4110-af13-4c8c82fd6d67)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Stone

![377475052-5ad666b3-1ee1-49e0-97bc-a4f1816ae969](https://github.com/user-attachments/assets/8d5b2c48-b805-4e84-b1d0-2c1928711ca9)

#### Output2 - Tumor
![377475565-93e6ea53-1778-4adc-ba51-ea888824f62b](https://github.com/user-attachments/assets/8066c87f-5085-4297-84b1-7dcc31a40e98)

#### Output3 - Cyst

![377475187-f4ae62af-3a65-43d0-9d5b-f309ce7fee41](https://github.com/user-attachments/assets/75a85414-c8fb-4aef-933a-867504d81a9d)

#### Output4 - Normal

![377475338-da7265eb-8ec3-48af-a7d0-392004d69093](https://github.com/user-attachments/assets/c99b5a52-e507-47a0-88fb-3b8f802baf33)


Detection Accuracy: 99.83%


## Results and Impact
<!--Give the results and impact as shown below-->
The project successfully classified kidney abnormalities (Normal, Cyst, Tumor, and Stone) using the VGG16 model, achieving high accuracy across all classes. The model demonstrated strong generalization with validation accuracy exceeding 99%, showing minimal overfitting. The confusion matrix and classification reports confirmed the model's ability to accurately detect abnormalities. This approach has the potential to significantly enhance diagnostic efficiency in medical imaging.


## Articles published / References
1. Maqsood, F., Zhenfei, W., Ali, M.M. et al. Artificial Intelligence-Based Classification of CT Images Using a Hybrid SpinalZFNet. Interdiscip Sci Comput Life Sci (2024). https://doi.org/10.1007/s12539-024-00649-4
2. Bingol H, Yildirim M, Yildirim K, Alatas B. 2023. Automatic classification of kidney CT images with relief based novel hybrid deep model. PeerJ Computer Science 9:e1717 https://doi.org/10.7717/peerj-cs.1717
3. Asif, S., Qurrat-ul-Ain, Awais, M. et al. IR-CNN: Inception residual network for detecting kidney abnormalities from CT images. Netw Model Anal Health Inform Bioinforma 12, 35 (2023). https://doi.org/10.1007/s13721-023-00431-4
4. Alzu’bi, D., Abdullah, M., Hmeidi, I., AlAzab, R., Gharaibeh, M., El-Heis, M., Almotairi, K. H., Forestiero, A., Hussein, A. M., & Abualigah, L. (2022).” Kidney tumor detection and classification based on deep learning approaches: A new dataset in CT scans”. Article ID 3861161, 22 pages https://doi.org/10.1155/2022/3861161




