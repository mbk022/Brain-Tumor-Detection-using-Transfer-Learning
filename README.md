# Brain-Tumor-Detection-using-Transfer-Learning
Brain tumor detection in MRI Images using various pre-trained deep learning models

This project explores the use of transfer learning for brain tumor detection in MRI images. The combined dataset of SARTAJ, Figshare, and BR35H offers a comprehensive representation of various tumor types, including Glioma, Meningioma, Pituitary, alongside healthy scans. Leveraging ImageDataGenerator, MRI image data is synthesized and augmented with diverse transformations. Fine-tuning follows, employing an array of optimizers and learning rates to enhance model adaptability and accuracy. Evaluation metrics including accuracy, AUC, precision, recall, and F1-score are used to assess model efficacy. Remarkably, both EfficientNetB0 and ResNet50 models attain an impressive accuracy of 96.64%, showcasing their robustness in tumor detection. However, amidst the contenders, the VGG16 model, paired with the Adam optimizer, emerges as the epitome of performance excellence, excelling across overall metrics. This study underscores the profound potential of transfer learning in medical imaging, presenting a cost-efficient and potent strategy for precise tumor diagnosis across various tumor types. The findings not only advance scientific understanding but also hold promise for transformative applications in clinical practice, revolutionizing patient care paradigms.

Project Architecture:

![Brain Architecture](https://github.com/mbk022/Brain-Tumor-Detection-using-Transfer-Learning/assets/72291169/59cc4962-97b8-4353-b810-79fcdc303b32)

The dataset used in this project is a combination of multiple datasets which consists of three different types of tumor images and no tumor samples. The datasets used are Figshare, SARTAJ and BR35H. The types of tumors in the combined datasets are Glioma, Meningioma, Pituitary and No tumor. The dataset sources are listed in references. The dataset consists of 7023 Brain MRI images. The data is split in two training and testing data. Training set consist of 5712 images and the Testing set consist of 1311 images. The Testing set is further divided in two, to make a new validation set to be used during training of models for validation during each epoch.

DataSet Link:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Results:
![image](https://github.com/mbk022/Brain-Tumor-Detection-using-Transfer-Learning/assets/72291169/88954385-aaf2-45d3-b64c-466a23ccf377)

![image](https://github.com/mbk022/Brain-Tumor-Detection-using-Transfer-Learning/assets/72291169/dab72ba1-0ff7-4950-8eaf-abbdccfa57d9)

![image](https://github.com/mbk022/Brain-Tumor-Detection-using-Transfer-Learning/assets/72291169/c96a2193-8d5d-4b04-860e-d6e6b4ad22de)

