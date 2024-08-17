This Project implements Genetic Algorithm Models for Software fault prediction and compares its performance with existing ML Models such as Decision Tree, SVM and ANN. 
Introduction. The Project's focus is to generate accurate fault prediction to optimize testing efforts and resource allocation in software development. We examine the effectiveness of Genetic Algorithm-based models for fault prediction, the impact of various sampling techniques, and the role of feature selection in enhancing model performance. 

DATASET : 
The input dataset(Open) is collected from Eclipse Repository. We consider Eclipse bug dataset and Defect Data set Collected from Jira website.
• Eclipse Dataset Repository URL : https://bug.inf.usi.ch/download.php
• Jira Dataset Repository URL : https://zenodo.org/records/3362613

DATA PRE-PROCESSING: 
The dataset is divided into training and testing sets, with preprocessing steps including standardization to ensure consistent data quality. This preparation is crucial for the effective application of machine learning models

IMPLEMENTATION:
The project evaluates several classifiers, including Decision Trees, Support Vector Machines, and Artificial Neural Networks, to determine their effectiveness in software fault prediction. It highlights the strengths of each algorithm, particularly the Decision Tree's interpretability and the ANN's ability to capture complex patterns. Genetic Algorithms are employed for hyper-parameter optimization, allowing for a systematic exploration of the parameter space to enhance model performance. The evolutionary nature of GA facilitates the discovery of optimal solutions through processes like selection, crossover, and mutation.

WORKFLOW:

![image](https://github.com/user-attachments/assets/cd4be2d6-2627-408e-919d-efeaa3e8665f)

CODE IMPLEMENTATION FLOW:

![image](https://github.com/user-attachments/assets/baaaf659-965b-4f3e-ad66-e1364e8f6b7d)

RESULT & ANALYSIS:
The performance of various models is assessed using metrics such as Precision, Recall, F1-Score, and Accuracy, with results indicating the superiority of GA-optimized models. The findings demonstrate that the GA-ANN model consistently outperforms other classifiers across different versions of the dataset.
