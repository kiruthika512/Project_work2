## Phishing Website Detection Using Machine Learning
It identifies phishing websites by analyzing their URL structure, content, and visual design, addressing advanced techniques like obfuscated URLs, malicious scripts, and visual mimicry.

Phishing attacks mimic legitimate websites to steal sensitive information, posing a significant cybersecurity threat. Traditional methods like blacklists and rule-based systems fail to detect evolving phishing techniques, such as obfuscated URLs, malicious content, and visual mimicry. The purpose of this project is to develop a robust, multi-modal phishing website detection system using machine learning to enhance user safety and security in the digital space. It identifies phishing websites by analyzing their URL structure, content, and visual design, addressing advanced techniques like obfuscated URLs, malicious scripts, and visual mimicry.

## Features
High Detection Accuracy
Real-Time Detection of Phishing websites
Cost Efficiency
Enhanced Cybersecurity

## Requirements
*Operating System: Requires a 64-bit OS (Windows 10, Ubuntu 20.04, or macOS) for compatibility with machine learning libraries.
*Development Environment: Python 3.7 or later is necessary for implementing phishing detection models.
*Machine Learning Libraries: Scikit-learn is used for training classifiers like Random Forest, Logistic Regression, SVM, and Gradient Boosting.
*Feature Extraction Libraries: BeautifulSoup for parsing HTML content and extracting phishing indicators.
*Data Normalization & Balancing: MinMaxScaler for feature scaling and SMOTE for handling class imbalances.
*Model Persistence: Joblib is used to save and load trained machine learning models.
*Automation & Screenshot Capture: Pyppeteer for capturing website screenshots and visual analysis.
*Version Control: Git is recommended for collaborative development and project version management.

## System Architecture
![Architecture](https://github.com/user-attachments/assets/b7c45f38-2c5b-4d48-96b7-ed0e79be27b9)


## Output

#### Output1 - Model Evaluation and Accuracy.

![Output 1](https://github.com/user-attachments/assets/1c7defd9-d6bb-409c-a4d6-0affeafe2760)


#### Output2 -  Final Output
![output 2](https://github.com/user-attachments/assets/f924b211-bc4b-4487-b039-dc60518d4afd)


Detection Accuracy: 96.8% (Random Forest Classifier)

## Results and Impact
The proposed system effectively detects phishing websites by analyzing URL structures for anomalies, evaluating website content using Machine learning models to identify malicious patterns, and utilizing Pyppeteer for capturing website screenshots and visual analysis. The use of ensemble classification ensures that predictions from all components are combined to improve accuracy and Use the trained ML model to classify the website as "Phishing" or "Legitimate."

## Articles published / References
U. Zara, K. Ayyub, H. Ullah Khan, A. Daud, T. Alsahfi and S. Gulzar Ahmad, "Phishing Website Detection Using Deep Learning Models," in IEEE Access, vol. 12, pp. 167072-167087, 2024, doi: 10.1109/ACCESS.2024.3486462.
L. R. Kalabarige, R. S. Rao, A. Abraham and L. A. Gabralla, "Multilayer Stacked Ensemble Learning Model to Detect Phishing Websites," in IEEE Access, vol. 10, pp. 79543-79552, 2022, doi: 10.1109/ACCESS.2022.3194672.
