# APT-Opcode-Detection

## Project Title - APT Group Detection Using Machine Learning on Opcodes

### Collaborators  
This project was a collaborative effort by:  
- **Philipa Kolade** <!--- (https://github.com/yourusername) -->
- **Smith Adoctor** <!--- (https://github.com/teammate1) -->
- **Dorcas Owusu** <!--- (https://github.com/teammate2) -->

### Project Summary  
This project applies machine learning techniques to classify Advanced Persistent Threat (APT) groups based on OpCode sequences extracted from malware samples. By analyzing 1-gram and 2-gram OpCode patterns, we evaluated the effectiveness of three classifiers: **Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree**.  

### Problem Statement  
APT groups often use unique malware variants with distinctive execution patterns. By analyzing OpCode sequences, we can develop machine learning models to attribute malware samples to specific APT groups, aiding in threat intelligence and malware classification.  

### Method
- **Pre-processed raw OpCode files** into **1-gram and 2-gram feature sets**.  
- Applied **three machine learning classifiers** (SVM, KNN, Decision Tree) to detect patterns in APT group behaviors.  
- Used **ANOVA F-test feature selection** to reduce dimensionality and **SMOTE** to balance the dataset.  
- Evaluated models based on **accuracy, precision, recall, F1-score, and confusion matrix analysis**.  

### Key Findings  
- **KNN** was the most consistent classifier, achieving **91.13% accuracy** in **1-gram analysis** and **89.60% in 2-gram analysis**.  
- **Decision Tree** performed well, with **91.13% accuracy in 2-gram classification**.  
- **SVM struggled**, achieving **66.97% accuracy (1-gram) and 70.34% accuracy (2-gram)**, often misclassifying overlapping opcode patterns.  
- Data imbalance and high dimensionality posed challenges, but SMOTE and feature selection improved results.  
- Certain APT groups (e.g., Scarlet Mimic, PittyTiger) had higher misclassification rates, indicating potential overlap in opcode behaviors.  

### Full Report  
The full paper has been made available in this repository

