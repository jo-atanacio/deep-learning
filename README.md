# Deep Learning for Pneumonia Detection

According to the [National Heart, Lung, and Blood Institute](https://www.nhlbi.nih.gov/health/pneumonia) Pneumonia is an infection that affects one or both lungs. It causes the air sacs, or alveoli, of the lungs to fill up with fluid or pus. Bacteria, viruses, or fungi may cause pneumonia. Symptoms can range from mild to serious and may include a cough with or without mucus (a slimy substance), fever, chills, and trouble breathing. How serious your pneumonia is depends on your age, your overall health, and what caused your infection.
To diagnose pneumonia, your healthcare provider will review your medical history, perform a physical exam, and order diagnostic tests such as a chest X-ray. This information can help determine what type of pneumonia you have.

In our case we are training a Convulotional Neural Network to detect accurately Pneumonia in chest X-rays.

## Dataset

![Chest X-Rays](https://github.com/jo-atanacio/deep-learning/assets/104554462/a385fed7-0909-4a8d-80e2-d9b3d7032769)

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

The dataset was obtained from Kaggle, and you can find it [here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Disclaimer

PROJECT IS ONGOING, AND RESULTS CANNOT BE REPRODUCED COMPLETELY

This personal project was done with the purpose of learning about CNN and deep learning.

This project was created in WSL2 with the purpose of using Tensorflow / Keras with a GPU.