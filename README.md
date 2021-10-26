# Brain-Tumor-Detection-Using-Keras-And-Pytorch: Overview-


* To Detect and Classify Brain Tumor using, CNN and TL; as an asset of Deep Learning and to examine the tumor position(segmentation).
* Prepared train and test data.
* Classifying brain images to one of the 4 categories: glioma_tumor, no_tumor, meningioma_tumor and pituitary_tumor.
* Data augmentation to include more images.
* Trained a CNN using keras and pytorch both.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, TensorFlow, Keras, cV2, glob and torch.

## Data Used
* About the data: A Brain tumor is considered as one of the aggressive diseases, among children and adults. Brain tumors account for 85 to 90 percent of all primary Central Nervous System(CNS) tumors. Every year, around 11,700 people are diagnosed with a brain tumor. The 5-year survival rate for people with a cancerous brain or CNS tumor is approximately 34 percent for men and36 percent for women. Brain Tumors are classified as: Benign Tumor, Malignant Tumor, Pituitary Tumor, etc. Proper treatment, planning, and accurate diagnostics should be implemented to improve the life expectancy of the patients. The best technique to detect brain tumors is Magnetic Resonance Imaging (MRI). A huge amount of image data is generated through the scans. These images are examined by the radiologist. A manual examination can be error-prone due to the level of complexities involved in brain tumors and their properties.

* **Data taken from kaggle** :https://www.kaggle.com/fahadmehfoooz/brain-tumor-detection-using-keras-and-pytorch/data

## Data Wrangling and Data Visualization
* Preparing the images by rescaling them.
* Visualizing the distribution of classes and the pictures of cells.
* Augmenting the data using an image data generator.
![alt text](https://github.com/fahadmehfooz/Brain-Tumor-Detection-Using-Keras-And-Pytorch-/blob/main/images/__results___62_0.png)

## Model Building 

First, I took a split on the data with training data as 80%. I tried to  model CNN with keras as well as pytorch.

* Used 4 convolutional layers.
* 1 dropout layer to avoid overfitting.
* Compiled the model using Adam optimizer.
## Model performance

**Results:**

* CNN - Train accuracy: 97.72%,  Validation accuracy: 93.38
