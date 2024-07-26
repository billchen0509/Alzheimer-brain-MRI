# Alzheimer brain MRI 
 Alzheimer disease detection and classification

# Problem Statement

Alzheimer's disease is a progressive neurological disorder that leads to memory loss, cognitive decline, and ultimately, the inability to perform everyday activities. It is the most common cause of dementia, affecting millions of people worldwide. Despite decades of research, the exact causes of Alzheimer's remain unclear, although it is believed to result from a combination of genetic, environmental, and lifestyle factors. Key pathological features include the accumulation of amyloid plaques and tau tangles in the brain, which disrupt neuronal communication and lead to cell death.

Thus, it is important to develop an artificial intelligence (AI) system capable of detecting Alzheimer's dementia in its early stages. Early detection is critical, as it allows for timely interventions that can significantly improve the quality of life and potentially extend the life expectancy of patients. By identifying the disease before severe cognitive decline sets in, healthcare providers can implement treatment plans and lifestyle changes that slow the progression of dementia, thus preserving the patient's cognitive functions and independence for a longer period.

The [dataset](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset/data) has four different catergories of Alzheimer's disease:
- Non Demented: patients who do not diagnozied with Alzheimer's disease.

- Very Mild Demented (Preclinical stage):This stage involves subtle memory lapses and slight forgetfulness, which can be mistaken for normal aging. Symptoms are not severe enough to impact daily life significantly, and Alzheimer's may not yet be diagnosable.

- Mild Demented (early stage): Characterized by noticeable memory issues and cognitive challenges, such as difficulty with planning and organizing. Individuals may struggle with remembering recent events and may experience changes in mood or personality, yet can still manage daily tasks with some support.

- Moderate Demented (middle stage): Marked by increased confusion, significant memory loss, and greater difficulty in communication and performing complex tasks. Behavioral changes and a higher need for daily assistance become evident, as independence decreases.

# Method 
In this notebook, I decided to focus on two tasks, Alzhemier Detection and Classification, where detection problem is to determine whether the patient carried the AD or not. 

On the other hand, the classification problem will focus on the differentiating the classes of AD stages.

The detection part used:
- PCA
- SVM

The classification part used:
- Convolutioal Neural Network
- RandomForest

# Reference:
https://www.kaggle.com/code/jeongwoopark/alzheimer-detection-and-classification-98-7-acc
https://www.kaggle.com/code/gonzalorecioc/alzheimer-brain-mri-classifier-effnetb0-99-acc
