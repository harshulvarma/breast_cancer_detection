# breast_cancer_detection

Invasive Ductal Carcinoma or IDC is the most common type of breast cancer and automated methods utilising machine learning in order to classify malignant and benign tissue can save valuable time and reduce error.

This script will identify IDC from a dataset which contains of ~5000 50x50 pixel RGB H&E stained breast cancer histoloy images.



The dataset was evaluated on various machine learning algorithms and neural network architectures and utilising data augmentation. Transfer Learning using a ResNet 50 model provided the best results in terms of accuracy metrics. Data was also balanced to have equally IDC+ and IDC- cases to yield reliable results.

Future changes would be to add a confusion matrix in order to make a more robust model since it is not desirable to identify IDC+ case as an IDC- case.
