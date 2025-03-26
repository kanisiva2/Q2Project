Convolutional Neural Networks (CNNs) are revolutionary implementations of neural networks used in image classification, though they sacrifice interpretability for accuracy, functioning as black-box models. Common machine learning and computer vision applications such as medicine require both accuracy and justification in the decision-making process, limiting learning methods including CNNs. Previous work combating these issues tend towards a combination of decision trees and neural networks, often forgoing accuracy in the process. This paper presents a novel approach to the aforementioned approach, enhancing CNN interpretability by combining multi-layer features from a pre-trained ResNet50 with a Decision Tree (DT) trained on the extracted features. Unlike existing approaches, this method maintains valuable intermediary data found in CNNs. To address the high dimensionality of CNN feature maps, we also test Principal Component Analysis (PCA) for dimensionality reduction before training the DT. Our results on the Pneumonia Chest X-ray dataset demonstrate that multi-layer feature extraction for CNN + DT achieves competitive transparency with improved accuracy, while PCA accelerates training without significant information loss.

Link to data:
https://drive.google.com/drive/folders/1R2qjKJRW7Y0XbdJ-yFMGdvPZRH2BphGQ?usp=sharing

How to Run Code:
1. Download and unzip the data folder linked above.
   
2. Create folders and upload files to match the file structure inside "chest_xray" folder. (First create two folders, "train" and "test", and then upload datasets as "Normal" and "Pneumonia" as they are presented in the "chest_xray" folder.
   
3. Run through each cell sequentially in the .ipynb.
