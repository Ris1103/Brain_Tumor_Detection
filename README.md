# Brain_Tumor_Detection
A Deep Learning model using Brain MRI scan to detect whether it has tumour or not. A brain tumor is a mass or boom of bizarre cells to your brain. It can begin to your mind, or most cancers someplace withinside the frame can unfold to the mind. The maximum not unusual place or not unusual place approach of detecting a tumor is Magnetic Resonance Imaging (MRI) test.

When we use deep learning algorithms on MRI pictures the brain tumor prediction is made in no time and with excessive accuracy which allows to offer remedy to patients. This prediction allows radiologists to make a short or short selection that results in the saving of many lives. In this proposed project, different ML techniques are used to discover the presence of a tumor with inside the mind after extensive experimentation and its feature is evaluated.


![Screenshot 2022-12-09 165043](https://user-images.githubusercontent.com/82215717/206691894-e2f76baf-f5ca-4b0d-8d2b-0543e8744000.jpg)




I've used Deep Learning model Convolutional Neural Network to make a predicting model which classifies brain MRI scans as with tumour and without tumour. We can use any IDE like Jupyter Notebook or Google Collab. In this project we used google collab. The dataset we used is BR35 Brain tumour Detection from kaggle and medicalMNIST HeadCT dataset. For data preprocessing, I have performed steps like image resizing, converting images as arrays, grayscaling etc.

For our labelled dataset I preprocessed the image separately for MRI scans with Tumors and MRI scans without Tumour and we will finally convert them into arrays. Once I normalized the images, the next step is to build the machine learning model. I used Deep Learning model CNN (Convolutional Neural) to build our predicting model. The data is split into training and test set. After splitting the data we will feed the images to our CNN model and train our model. In this model I used RelU activation function in the training model and used adam optimizer to optimize the model. Once the model was trained I used binary Cross Entropy loss to check accuracy of the model.
