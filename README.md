## Kaggle SIIM ISIC Melanoma Classification
Kaggle competition to identify melanoma in lesion images.


Check code on [Kaggle](https://www.kaggle.com/muhakabartay) and on this [GitHub](https://github.com/kabartay/kaggle-siim-isic-melanoma-classification) repository. 
- | [Kaggle](https://www.kaggle.com/muhakabartay/siim-isic-melanoma-classification-eda-dicom) | [GitHub](https://github.com/kabartay/kaggle-siim-isic-melanoma-classification/blob/ae62541ae7f7a02f95d1d16910e8e8b3709d362e/siim-isic-melanoma-classification-eda-dicom.ipynb) | SIIM-ISIC Melanoma Classification EDA with **DICOM**  
Notebook provides EDA with exploration of DICOM image format. 


- | [Kaggle](https://www.kaggle.com/muhakabartay/siim-isic-melanoma-classification-efficientnet) | [GitHub](https://github.com/kabartay/kaggle-siim-isic-melanoma-classification/blob/ae62541ae7f7a02f95d1d16910e8e8b3709d362e/siim-isic-melanoma-classification-efficientnet.ipynb) | SIIM-ISIC Melanoma Classification **EfficientNet** (Keras)  
Notebook provides EDA, EfficientNetB**x** model (**x** by your choice),train/validation/evaluation using TFRecords, model tuning, kFold validation,  data augmentation, and some post-processing.  


- | [Kaggle](https://www.kaggle.com/muhakabartay/keras-siim-isic-melanoma-classification-resnet?scriptVersionId=65018173) | [GitHub](https://github.com/kabartay/kaggle-siim-isic-melanoma-classification/blob/ae62541ae7f7a02f95d1d16910e8e8b3709d362e/keras-siim-isic-melanoma-classification-resnet.ipynb) | SIIM-ISIC Melanoma Classification **ResNet** (Keras)   
Notebook provides EDA, ResNet50 model,train/validation/evaluation using original images, and data augmentation.  


- | [Kaggle](https://www.kaggle.com/muhakabartay/public-blender-with-rank-data-0-946) | [GitHub](https://github.com/kabartay/kaggle-siim-isic-melanoma-classification/blob/ae62541ae7f7a02f95d1d16910e8e8b3709d362e/public-blender-with-rank-data-0-946.py) | Public Blender with **Rank Data**      
Notebook provides simple blending strategy with rank data on some public solutions.  


&nbsp;


<img align="left" src="https://raw.githubusercontent.com/kabartay/kaggle-siim-isic-melanoma-classification/master/materials/logo.png" data-canonical-src="https://raw.githubusercontent.com/kabartay/kaggle-siim-isic-melanoma-classification/master/materials/logo.png" width="275" height="275" />

Skin cancer is the most prevalent type of cancer. **Melanoma**, specifically, is responsible for **75%** of skin cancer deaths, despite being the least common skin cancer. The American Cancer Society estimates over 100,000 new melanoma cases will be diagnosed in 2020. It's also expected that almost 7,000 people will die from the disease. As with other cancers, early and accurate detection—potentially aided by data science—can make treatment more effective.

Currently, dermatologists evaluate every one of a patient's moles to identify outlier lesions or “ugly ducklings” that are most likely to be melanoma. Existing AI approaches have not adequately considered this clinical frame of reference. Dermatologists could enhance their diagnostic accuracy if detection algorithms take into account “contextual” images within the same patient to determine which images represent a melanoma. If successful, classifiers would be more accurate and could better support dermatological clinic work.

As the leading healthcare organization for informatics in medical imaging, the [Society for Imaging Informatics in Medicine (SIIM)](https://siim.org/)'s mission is to advance medical imaging informatics through education, research, and innovation in a multi-disciplinary community. SIIM is joined by the [International Skin Imaging Collaboration (ISIC)](https://www.isic-archive.com/), an international effort to improve melanoma diagnosis. The ISIC Archive contains the largest publicly available collection of quality-controlled dermoscopic images of skin lesions.

In this competition, you’ll identify melanoma in images of skin lesions. In particular, you’ll use images within the same patient and determine which are likely to represent a melanoma. Using patient-level contextual information may help the development of image analysis tools, which could better support clinical dermatologists.

Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Image analysis tools that automate the diagnosis of melanoma will improve dermatologists' diagnostic accuracy. Better detection of melanoma has the opportunity to positively impact millions of people.

<img align="left" src="https://raw.githubusercontent.com/kabartay/kaggle-siim-isic-melanoma-classification/master/materials/melanoma.png" data-canonical-src="https://raw.githubusercontent.com/kabartay/kaggle-siim-isic-melanoma-classification/master/materials/melanoma.png" width="1200" height="300" />
