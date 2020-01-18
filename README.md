# ChemicalCompounds
Task: The given dataset contains details about organic chemical compounds including their chemical features, isomeric conformation, names and the classes in which they are classified. 
The compounds are classified as either ‘Musk’ or ‘Non-Musk’ compounds. 
The task is to build a classification model on the given data using any Deep Learning approach.
There are 3 main steps: Data preprocessing, model training and getting the performance measures.
Data pre-processing : To handle missing values, deleting data can reduce the dataset by too much.
A more dynamic way of handling missing values is by imputing them.
I chose the dynamic way of imputing missing values using the iterative imputation.
Model : I trained a CNN model where I used 2 convolution and 2 dense layers in the network.
Performance measures :
f1_score: 0.9251336898395722
recall: 0.8963730569948186
precision: 0.9558011049723757
Validation Loss: 0.0635519825430079
Validation Accuracy: 0.9787878787878788
