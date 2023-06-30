# Skin Cancer Detector using Tensorflow and ML


# Motivation

Skin cancer is a pervasive and growing concern worldwide. According to the World Health Organization, each year, there are over 5 million new cases of skin cancer diagnosed globally. In some regions, skin cancer rates have been increasing by as much as 10-15% annually. These numbers highlight the urgent need for innovative solutions that can aid in early detection and intervention.

Recognizing the limitations and challenges faced by healthcare systems, I have harnessed the power of machine learning and computer vision to create an AI system that shows promise in identifying potential indicators of skin cancer. By leveraging vast amounts of visual data, I have aimed to develop a tool that can complement the expertise of dermatologists and potentially enhance diagnostic accuracy.


 # Methods and Technology

 The data was acquired from the organization ISIC: https://www.isic-archive.com/

 Pandas: Used to store metadata of images and help with creating CSV files to classify and read the images as benign and malignant
 Tensorflow and Keras: Used in modeling and processing image data, adoption of inception_v3 model, and training of Convolutional Neural Network
 Numpy: Used in data processing especially reshaping for large multi dimensional arrays
 SKlearn: Used to generate confusion matrix -- graphical representation of one way we can measure our CNN's accuracy


 # Inception V3 Model Represented Graphically

 ![image](https://github.com/teddy-ross/skinCancerDetection/assets/116533652/a8d9639e-d37d-49a3-8176-cc05331d2639)


 # Results, Confusion Matrix, and Type 1 and Type 2 error prevalence

 Here is a reflection of my results and the chance of false positives and negatives

 Note: Tensorflow gives about **80% accuracy** for the CNN with method .evaluate
![confusionmatrix](https://github.com/teddy-ross/skinCancerDetection/assets/116533652/7309dee1-d127-4c3c-b8c2-802c555b4b44)

 # Resources Consulted

 https://cloud.google.com/tpu/docs/inception-v3-advanced 
 
 https://iopscience.iop.org/article/10.1088/1742-6596/1911/1/012032/pdf
 
 https://www.researchgate.net/publication/343409875_Deep_Convolutional_Neural_Network_with_TensorFlow_and_Keras_to_Classify_Skin_Cancer_Images

 
