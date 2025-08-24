**🖥️ SVM & DECISION TREE PRACTICE TASKS**

This repository contains practice exercises for SUPPORT VECTOR MACHINES (SVM) and DECISION TREES, covering both classification and regression problems. Visualizations are included to make model behavior clearer. 📊

**📌 TASKS OVERVIEW**

**Q1) LINEAR SEPARABILITY (BINARY CLASSIFICATION)**

DATASET: svm_linear.csv (200 rows, 2 features)

TASK: Train an SVM WITH LINEAR KERNEL to classify two classes.

DELIVERABLES:

✅ Model accuracy

🖼️ Decision boundary plot




**Q2) EFFECT OF KERNEL (BINARY CLASSIFICATION)**

DATASET: svm_kernel.csv (200 rows, circular pattern)

TASK: Train SVM WITH LINEAR KERNEL and SVM WITH RBF KERNEL.

DELIVERABLES:

✅ Compare accuracy of linear vs RBF

🖼️ Plot decision boundaries for both kernels



**Q3) MULTICLASS CLASSIFICATION WITH SVM**

DATASET: svm_multi.csv (3 classes, 2 features, 300 rows)

TASK: Train SVM WITH RBF KERNEL for 3-class classification.

DELIVERABLES:

✅ Confusion matrix

✅ Accuracy





**Q4) SIMPLE CLASSIFICATION TREE**

DATASET: dt_class.csv (200 rows, 2 features + label)

TASK: Train a DECISION TREE CLASSIFIER.

DELIVERABLES:

🖼️ Visualize the tree

✅ Report test accuracy




**Q5) EFFECT OF TREE DEPTH**

DATASET: dt_depth.csv (200 rows, 2 features)

TASK: Train Decision Trees with MAX_DEPTH = 2, 5, NONE

DELIVERABLES:

✅ Compare train and test accuracy for different depths




Q6) REGRESSION TREE

DATASET: dt_reg.csv (200 rows, x → y with noise)

TASK: Fit DECISION TREEREGRESSOR to predict y.

DELIVERABLES:

✅ Compare RMSE for depths 2, 5, NONE





**🛠️ TOOLS & LIBRARIES**

**Python 🐍**

scikit-learn (SVM, Decision Trees, metrics)

matplotlib / mlxtend for visualization 📊

pandas / numpy for data handling

**⚡ HOW TO RUN**

Install required libraries:

pip install scikit-learn matplotlib pandas numpy mlxtend


Run the Jupyter Notebook / Python script for each task.

Check outputs: accuracy, confusion matrix, RMSE, and plots.



**🎯 KEY LEARNING POINTS**

SVM: Understanding linear vs non-linear kernels, binary vs multiclass.

DECISION TREE: Understanding tree depth, overfitting/underfitting, regression vs classification.


Visualization helps in understanding model decisions clearly 👀
