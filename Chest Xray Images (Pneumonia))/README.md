# Chest X-Ray Images (Pneumonia)
### Content
- The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). 
- There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

### Source
- Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. 
- All chest X-ray imaging was performed as part of patients’ routine clinical care.
- For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. 
- The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. -  - In order to account for any grading errors, the evaluation set was also checked by a third expert.

### Project Overview
- This is a Classification Problem.
- **Objective:** To classify chest X-ray images into two categories: Pneumonia and Normal using a CNN model.

**Observations:**
    
    1. This is an Image Classification Porblem
    2. The CNN Model takes the Xray scan image as input and predicts if the patient is NORMAL or infected with PNEUMONIA
    3. The Model performance is as foolows:
    - trianing prediction accuracy of 92.06% with loss of 0.1797 and 
    - test preiction accuracy of 89.75% with loss of 0.2990
    4. Accuracy can be further improved by tuning the model paramaters as:
    - optimizer
    - learning_rate
    - no. of convolution and pooling layers
    - no. of Dense layers
