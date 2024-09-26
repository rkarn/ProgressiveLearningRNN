# ProgressiveLearningRNN

This repository contains the source code to reproduce the results of our paper:

`Karn, Rupesh Raj, Johann Knechtel, and Ozgur Sinanoglu. "Progressive Learning With Recurrent Neural Network for Sequence Classification." IEEE Transactions on Circuits and Systems II: Express Briefs (2023).` 

Also submitted in  `Transactions in Circuit and System (TCAS-II)`  (Under Review).

Download the formatted MNIST and Devnagri datasets from the following link. 

Devnagri: https://drive.google.com/file/d/14ZiKWAhc_VYO-pL9Nfs3Zcv9-TVJyz-f/view?usp=sharing 

MNIST: https://drive.google.com/file/d/13u7LiL5NyP8DlajGd1DzOGs5wEvBAYgI/view?usp=sharing  

Install Raytune as per the documentation given at https://docs.ray.io/en/latest/tune/getting-started.html#tune-tutorial 

Run the Jupyter notebook titled "MNIST Dataset task creation.ipynb" and "Devnagri Dataset task creation.ipynb" to create progressive tasks. Then run the remaining notebook to perform RNN training validation. 
