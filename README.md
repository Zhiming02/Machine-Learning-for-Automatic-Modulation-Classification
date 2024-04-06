# ML-for-AMC
This is a project for using Machine Learning (CNN) model on automatic modulation classifiction 

ML model was trained on constellation graph of different modulation schemes

Constellation dataset is generated by Simulink & MATLAB (in Dataset Generation file, model parameters are defined in MATLAB, then by changing the basedband modulation block in Simulink can generate the constellation image of each scheme)

PyTorch_ML is the code of training and testing ML models by using PyTorch
https://pytorch.org/

Add_loss code is the code of training ML model with extend knowledge-based loss function

Dynamic_Quantization is the code for quantizing the linear layer of pre-trained ML model using 'Dynamic Quantization' in PyTorch：
https://pytorch.org/blog/introduction-to-quantization-on-pytorch/

Knowledge of Signal Processing, Communication System, Modulation can be found in book:
https://www.rfsocbook.com/
