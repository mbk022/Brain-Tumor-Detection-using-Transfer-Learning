# Brain-Tumor-Detection-using-Transfer-Learning
Brain tumor detection in MRI Images using various pre-trained deep learning models

This project explores the use of transfer learning for brain tumor detection in MRI images. The combined dataset of SARTAJ, Figshare, and BR35H offers a comprehensive representation of various tumor types, including Glioma, Meningioma, Pituitary, alongside healthy scans. Leveraging ImageDataGenerator, MRI image data is synthesized and augmented with diverse transformations. Fine-tuning follows, employing an array of optimizers and learning rates to enhance model adaptability and accuracy. Evaluation metrics including accuracy, AUC, precision, recall, and F1-score are used to assess model efficacy. Remarkably, both EfficientNetB0 and ResNet50 models attain an impressive accuracy of 96.64%, showcasing their robustness in tumor detection. However, amidst the contenders, the VGG16 model, paired with the Adam optimizer, emerges as the epitome of performance excellence, excelling across overall metrics. This study underscores the profound potential of transfer learning in medical imaging, presenting a cost-efficient and potent strategy for precise tumor diagnosis across various tumor types. The findings not only advance scientific understanding but also hold promise for transformative applications in clinical practice, revolutionizing patient care paradigms.

Project Architecture:

![Brain Architecture](https://github.com/mbk022/Brain-Tumor-Detection-using-Transfer-Learning/assets/72291169/59cc4962-97b8-4353-b810-79fcdc303b32)

The dataset used in this project is a combination of multiple datasets which consists of three different types of tumor images and no tumor samples. The datasets used are Figshare, SARTAJ and BR35H. The types of tumors in the combined datasets are Glioma, Meningioma, Pituitary and No tumor. The dataset sources are listed in references. The dataset consists of 7023 Brain MRI images. The data is split in two training and testing data. Training set consist of 5712 images and the Testing set consist of 1311 images. The Testing set is further divided in two, to make a new validation set to be used during training of models for validation during each epoch.

DataSet Link:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Results:

Model	Accuracy (%)	AUC	Precision (%)	Recall (%)	F1-Score (%)
VGG16-Adam	96.34	0.99	96.34	96.34	96.34
VGG16-SGD	96.03	0.99	96.26	96.13	96.22
VGG19-Adam	92.83	0.98	93.94	93.89	93.92
VGG19-SGD	95.88	0.98	94.45	94.38	94.42
Xception-Adam	88.26	98.72	93.39	93.11	93.25
Xception-SGD	76.37	98.33	90.81	90.11	90.46
EfficientNetB0-Adam	96.64	98.52	91.64	91.03	91.33
EfficientNetB0-SGD	95.73	98.67	92.15	91.55	91.85
EfficientNetV2B0-Adam	94.96	98.72	92.46	91.93	92.19
EfficientNetV2B0-SGD	96.18	98.8	92.84	92.35	92.6
ResNet50-Adam	96.64	98.87	93.2	92.74	92.97
ResNet50-SGD	96.03	98.95	93.44	93.01	93.22
ResNet50V2-Adam	43.9	96.38	96.59	74.74	84.27
ResNet50V2-SGD	90.94	97.71	93.57	82.06	87.44
DenseNet121-Adam	92.53	97.81	93.49	82.75	87.8
DenseNet121-SGD	92.53	97.91	93.45	83.33	88.11
InceptionV3-Adam	83.99	97.68	92.91	83.33	87.86
InceptionV3-SGD	48.32	93.33	94.26	63.3	75.74
