<div align="center">

# 🤖 Applied AI Solutions for Business and Technology<br>

**Kevinkumar Bhingaradiya**<br>
*Applied AI for Business Learning Portfolio – Hands-On Projects*<br>

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/stable/user_guide.html)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/api_docs)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/api/)
<br>

</div>

---

## 🧠 Reflection<br>

### 📚 What I learned across all modules<br>

Across seven projects built on Géron's *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (3rd ed.), I learned the full machine learning workflow. The biggest lesson was that a model has to be judged by evidence, not by one headline number.<br>

- **Project 1:** tuning a Random Forest pipeline with RandomizedSearchCV cut the error of my California housing price predictions from about **$68,600** with Linear Regression to about **$42,100**.<br>
- **Project 2:** my MNIST 5-detector was right about **96%** of the time, yet a dummy model that never predicts a 5 already scores **91%**; the confusion matrix showed that it found only **65%** of the real 5s, and raising its precision to 90% cut its recall to **48%**.<br>
- **Project 3:** scaling the features lifted a linear SVM on the Wine dataset from **91%** to **97.7%** accuracy, which showed me how much data preparation matters.<br>
- **Project 4:** an unrestricted Decision Tree scored **100%** on its training data but only **81%** on the test set, while a tree limited to 17 leaves reached **86%** and a majority vote of 1,000 small trees reached **87%**, which made overfitting concrete.<br>
- **Project 5:** PCA kept **95%** of the variance of MNIST with **154** features and made an SGD classifier faster and more accurate, but it made a Random Forest slower and less accurate, which showed me that no technique is a rule.<br>
- **Projects 6 and 7:** Keras and TensorFlow turned these ideas into neural networks for images and text.<br>

### 🛠️ Skills I developed<br>

| Area | What I did |
|:--|:--|
| **Data preprocessing** | Explored and prepared real datasets (California housing, MNIST, Wine, the moons dataset and 5,574 SMS messages): split training and test sets, scaled features with StandardScaler, built preprocessing pipelines, and turned text into numbers through lowercasing, punctuation and stopword removal, tokenization and a 7,695-word Bag-of-Words.<br> |
| **Model tuning** | Used cross-validation, GridSearchCV and RandomizedSearchCV with linear models, SVMs, Decision Trees and Random Forests; a randomized search over C and gamma gave an RBF-kernel SVM **97.8%** accuracy on the Wine test set.<br> |
| **Deep learning** | Found a learning rate by growing it exponentially until the loss shot up, trained a 266,610-parameter MLP with early stopping and checkpoints to **97.7%** test accuracy on MNIST, and built a Keras model with an Embedding layer that classified **98.6%** of the test SMS messages correctly.<br> |
| **Visualization** | Matplotlib maps and scatter plots, confusion matrices, precision/recall and ROC curves, decision-boundary plots, Graphviz trees and flowcharts, TensorBoard learning curves and t-SNE maps of 5,000 handwritten digits.<br> |
| **Debugging** | Debugged notebooks methodically, tracing each error to its cause and documenting the fix.<br> |

### 💼 How these projects prepare me for real-world ML tasks<br>

These projects mirror the decisions a machine learning engineer makes on real business problems.<br>

- **Metrics that match the business cost:** data such as fraud, churn or spam is usually imbalanced, so I now choose precision, recall and F1 according to the cost of each kind of error. In my spam filter, only **2 of 966** legitimate messages were flagged as spam while **135 of 149** spam messages were caught, which tells users far more than the **98.6%** headline accuracy.<br>
- **Sound evaluation habits:** I keep the test set untouched until the end, compare every model with a simple baseline, treat preprocessing and dimensionality reduction as choices to test, and measure overfitting instead of discovering it in production.<br>
- **End-to-end delivery:** Project 7 took me from raw text to a trained model, an evaluation, a flowchart of the process and an interface where a user can classify a new message, the same shape as a text classification service in production.<br>
- **From notebook to product:** combined with my experience as a software engineer, these skills prepare me to turn models into reliable, explainable features that a business can trust.<br>

---

## 🤝 AI Statement<br>

> I used **Claude**, the AI assistant made by Anthropic, through Claude Code as a coding and writing aid in Projects 2 to 7, and each of those notebooks ends with its own AI statement. For coding, Claude generated the digit-3 classifier in Project 2, as that assignment required, trimmed the textbook notebooks to the sections each assignment asked for, wrote the network diagram in Project 6 and the SMS spam pipeline, flowchart and interface in Project 7, and ran the notebooks to confirm that every cell executes. For debugging, it traced the errors I ran into, mostly NameErrors caused by imports that were removed with the trimmed chapter code, plus a missing TensorBoard extension and a Windows PATH problem, and it made the Project 7 results repeatable by setting random seeds. For explanations, it helped me draft my text-box answers from Géron (2022) and draft this README from my own results. I checked every explanation against the textbook and the notebook outputs, made the final decisions myself, and I take responsibility for all of the work in this portfolio.<br>

---

## 📂 Projects completed in this course<br>

| Project | Dataset | Key techniques |
|:--|:--|:--|
| **Project 1 Chapter 1: Machine Learning Review**<br> | California housing | Linear Regression, Decision Tree and Random Forest regression, K-Means geo clusters, cross-validation, GridSearchCV, RandomizedSearchCV<br> |
| **Project 2 Chapter 3: Classification**<br> | MNIST | SGD binary classifier, confusion matrix, precision/recall, ROC and AUC, Random Forest comparison<br> |
| **Project 3 Chapter 5: Support Vector Machines**<br> | Wine | LinearSVC, feature scaling, RBF-kernel SVC, RandomizedSearchCV<br> |
| **Project 4 Chapter 6: Decision Trees**<br> | Moons | Decision Tree, GridSearchCV, a hand-built Random Forest (majority vote of 1,000 trees)<br> |
| **Project 5 Chapter 8: Dimensionality Reduction**<br> | MNIST | PCA, Random Forest vs. SGD, t-SNE, LLE, MDS, LDA<br> |
| **Project 6 Chapter 10: Artificial Neural Networks**<br> | MNIST | Keras MLP, learning-rate search, early stopping, checkpoints, TensorBoard<br> |
| **Project 7 Chapter 16: Natural Language Processing**<br> | SMS Spam Collection | Text preprocessing, Bag-of-Words, Embedding model, Graphviz flowchart, interactive interface<br> |

---

## 🔗 Link to the Project Notebooks<br>

<div align="center">

[![Open the project notebooks in Google Drive](https://img.shields.io/badge/Google%20Drive-Open%20the%20project%20notebooks-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1lkgZllWWodxgPDJwie8g0KBmfP7yD59g?usp=sharing)<br>
</div>

All seven projects are in one shared Google Drive folder, with one subfolder per module:<br>

```text
📁 AI_For_Business/
├── 📁 Module 1/  →  Project 1 · Chapter 1: Machine Learning Review
│   ├── 📄 Module 1_Project 1.docx
│   └── 🖼️ Module 1 Assignment Sign in or Create a Google Colaboratory Account.png
├── 📁 Module 2/  →  Project 2 · Chapter 3: Classification
│   └── 📓 03_classification.ipynb
├── 📁 Module 3/  →  Project 3 · Chapter 5: Support Vector Machines
│   └── 📓 Module_3_Assignment_Project_3.ipynb
├── 📁 Module 4/  →  Project 4 · Chapter 6: Decision Trees
│   └── 📓 Kevinkumar_Bhingaradiya_Assignment_Project_4.ipynb
├── 📁 Module 5/  →  Project 5 · Chapter 8: Dimensionality Reduction
│   └── 📓 Kevinkumar_Bhingaradiya_Assignment_Project_5.ipynb
├── 📁 Module 6/  →  Project 6 · Chapter 10: Artificial Neural Networks
│   ├── 📓 Kevinkumar_Bhingaradiya_Assignment_Project_6_2nd.ipynb   ⭐ final version
│   └── 📓 Kevinkumar_Bhingaradiya_Assignment_Project_6.ipynb       (first version)
└── 📁 Module 7/  →  Project 7 · Chapter 16: Natural Language Processing
    └── 📓 Kevinkumar_Bhingaradiya_Assignment_Project_7.ipynb
```

> 💡 **Tip:** to run a notebook, open it in the Drive folder and choose **Open with → Google Colaboratory**.<br>

---

*Textbook: Géron, A. (2022). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (3rd ed.). O'Reilly Media.*<br>
