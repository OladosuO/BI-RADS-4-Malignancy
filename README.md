Breast cancer is the leading cause of cancer-related mortality and morbidity among women globally. However, BI-RADS Category 4 includes a wide range of malignancy probabilities (over 2% to 95%), leading to potential overdiagnosis and unnecessary procedures like biopsies, which can cause physical trauma and financial strain.
To address these issues, we have developed a ** MobileNet-CBAM model**, which integrates MobileNet with the Convolutional Block Attention Module (CBAM) to enhance the prediction of malignancy in BI-RADS Category 4 cases.
Model explanations are provided using SHAP for better clinical understanding and trust.
![image](https://github.com/user-attachments/assets/de7a0043-732b-4fb4-80d0-bf211af8a77f)

![image](https://github.com/user-attachments/assets/c8e7a6df-5e98-4cc5-b4df-6d2bedff2344)

**Linnk to the article**
https://link.springer.com/chapter/10.1007/978-3-031-77789-9_10

**Dataset**
https://www.cancerimagingarchive.net/collection/cdd-cesm/

**Citation**
@InProceedings{10.1007/978-3-031-77789-9_10,
author="Oladimeji, Oladosu
and Ayaz, Hamail
and McLoughlin, Ian
and Unnikrishnan, Saritha",
editor="Mann, Ritse M.
and Zhang, Tianyu
and Tan, Tao
and Han, Luyi
and Truhn, Danial
and Li, Shuo
and Gao, Yuan
and Doyle, Shannon
and Mart{\'i} Marly, Robert
and Kather, Jakob Nikolas
and Pinker-Domenig, Katja
and Wu, Shandong
and Litjens, Geert",
title="Optimizing BI-RADS 4 Lesion Assessment Using Lightweight Convolutional Neural Network with CBAM in Contrast Enhanced Mammography",
booktitle="Artificial Intelligence and Imaging for Diagnostic and Treatment Challenges in Breast Care",
year="2025",
publisher="Springer Nature Switzerland",
address="Cham",
pages="96--106",
abstract="Breast cancer is the leading cause of cancer-related mortality and morbidity among women worldwide. Early detection plays a crucial role in improving survival rates and BI-RADS classification is one of the effective ways of predicting breast cancer. However, BI-RADS Category 4 encompasses a broad spectrum of malignancy probabilities, ranging from over 2{\%} to 95{\%}. Due to the wide malignancy likelihood range and the ambiguous qualitative attributes of BI-RADS 4, patients are subjected to overdiagnosis and unnecessary procedures, such as biopsy, which entail a certain degree of physical trauma as well as financial strain. This study proposed a lightweight CNN where MobileNet serves as the backbone architecture, augmented with the Convolutional Block Attention Module (CBAM), resulting in the MobileNet-CBAM model. The model demonstrated good performance in discriminating BI-RADS 4 category malignant and benign cases in Contrast Enhanced Spectral Mammogram (CESM) with a prediction of 82{\%}, 82{\%} and 0.91 for accuracy, f1-score and roc-auc respectively. Additionally, for clinical friendliness, the model explanation was given using SHAP. Hence, the model presents potential utility in predicting breast cancer for lesions categorized as BI-RADS category 4 in breast imaging.",
isbn="978-3-031-77789-9"
}


**Contact**
Email: S00243011@atu.ie
