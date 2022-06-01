# CS235 Project: Predict Covid 19 Spread
### Overview
We use data mining techniques to predict the spread of COVID-19 and the implemented methods include Markov Chain, Random Forest, Neural Networks, Adaboosting, and Support Vector Machines.


### Main Packages Installation Requirements

Our project is written with Python 3. To run our jupyter notebooks and files, the packages below are required to be installed:

- numpy
- pandas
- scikit-learn
- matplotlib
- torchvision=0.8.2
- pytorch=1.7.1
- tensorflow=2.1.0
- keras=2.2.4

### Folder Structure and Description
Our code files are organized as follows:
```
| AdaBoostR2
│   ├── AdaBoostR2.py
│   ├── test.csv
│   └── train.csv
├── Complete Covid Dataset
│   └── covid_19_clean_complete.csv
├── Data Cleaning 2.ipynb
├── Data Cleaning.ipynb
├── Markov.ipynb
├── NeuralNetworks
│   └── Neural_Network.ipynb
├── README.md
├── Random Forest
│   ├── CS 235 Covid-19 Project RF from-scratch by JD.ipynb
│   ├── CS 235 Covid-19 Project RF sklearn by JD.ipynb
│   ├── test.csv
│   └── train.csv
├── SVM
│   ├── SVM Predictions - Scratch.ipynb
│   └── SVM Predictions.ipynb
├── Team 3 - Project Proposal.pdf
├── [Cleaned] Complete Data
│   ├── test.csv
│   └── train.csv
└── [Cleaned] Forecasting Data
    ├── test.csv
    └── train.csv
```

- AdaBoostR2: This folder contains both the library  implementation, and our from scratch implementation of the AdaBoost algorithm. The train.csv and test.csv are the preprocessed data used by the ```AdaBoostR2.py```
- ```Markow.ipynb```: We put our implementaion of Markov Chain method in this jupyter notebook.
- Neural Networks: The ```Neural_Network.ipynb``` presents both the data preprocessing and the network architectures including MLP-shallow, MLP-deeper as well as the ResNet-Regression. The results is run with the optimal hyperparameter values.
- SVM: The ```SVM Predictions - Scratch.ipynb``` contains the implementation and results of our from scratch implementation of the support vector machine (SVM), while the ```SVM Predictions.ipynb``` contains the library code.
- Random Forest: The ```CS 235 Covid-19 Project RF from-scratch by JD.ipynb``` contains the implementation and results of our from scratch implementation of the random forest, while the ```SVM Predictions.ipynb``` contains the library code.
- Complete Covid Dataset: We put the original, unpreprocessed data in this folder.
- [Cleaned] Complete Data: We put the preprocessed COVID-19 data from January 2020 to late July 2020 in this folder.
- ```Data Cleaning.ipynb, Data Cleaning 2.ipynb```: Data preprocessing.






