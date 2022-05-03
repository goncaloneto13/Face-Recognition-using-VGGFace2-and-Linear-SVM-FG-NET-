# Face-Recognition-using-VGGFace2-and-Linear-SVM (FG-NET)


The goal is to develop a system that uses a face recognition approach, focusing on age invariance, that returns good results compared to the results obtained in the literature review.
The approach studied uses deep Convolutional Neural Networks - CCNs, pretrained by the VGGFace2 dataset, to extract feature descriptors from face images and classify with the Linear SVM classification algorithm. As can be seen throughout the paper, the approach returned 89.9% accuracy using the FG-NET dataset with 1002 images. And using the CACD dataset, which contains 163,446 images divided into four different subsets, three sets for training and one for testing, the approach returned 85.2%, 82.4%, and 88.2% accuracy for each model trained with a different training set
