# Retinal-Lesions-Segmentation
Retinal Lesions Segmentation in Fundus Color Images

Diabetic retinopathy (DR) is the leading cause of complete or partial blindness among
people with diabetes mellitus. DR can be diagnosed early with the identification of Retinal Lesions on the surface of the eye. However, early diagnosis faces multiple challenges including lack of skilled manpower, knowledge on the disease and complexity in identification because most cases of diabetic retinopathy are identified only when they become severe. Therefore, automatic DR detection from fundus images can offer
strong clinical value. We trained our models on the publicly available labeled dataset for DR, the Indian Diabetic Retinopathy Image Dataset (IDRiD). It presents retinal fundus images with pixel-level annotations of four distinct lesions: microaneurysms (MA), hemorrhages (HE), soft exudates (SE), and hard exudates (EX). In this project, we implemented a Machine Learning (ML) framework on Retinal fundus images from the IDRiD dataset to segment the retinal lesions. For ML, the images were first processed using advanced image analysis methods in order to detect candidate lesions and then segmented using ML models including SVM, KNN, LGBM, and Random Forest. Among them, the best classifier was found to be Random Forest with an F1 score of 0.85 for Red Lesions (MA,HE) and an F1 Score of 0.91 for the Exudates (EX,SE). The AUPR Curve for the whole test images of the four lesions in the IDRiD dataset was calculated using the Trapezoidal rule. We achieved AUPR = 0.45, 0.10, 0.06, and 0.21 for EX, SE, MA, and HE, respectively.

![image](https://user-images.githubusercontent.com/19288227/179268441-fc40f454-3aa6-4799-8250-e2cfbe7d154b.png)

![image](https://user-images.githubusercontent.com/19288227/179268617-d9cd72a3-9af5-4a33-b149-3b9f689f7d04.png)
