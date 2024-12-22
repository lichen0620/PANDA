# PANDA

This is the official codebase for the paper: [PANDA: Patch-Aware Graph Network with Dual Alignment for Time Series Forecasting]



## Preparation

1. Install python==3.9 and Pytorch (>=1.12.0) and other necessary dependencies.
```
pip install -r requirements.txt
```
2. All the five benchmark datasets can be obtained from [Google Drive]
(https://drive.google.com/file/d/1CC4ZrUD4EKncndzgy5PSTzOPSqcuyqqj/view?usp=sharing) 
3. All datasets are stored in the folder `data` 
4. Run by:
```
python run.py --dataset <dataset_name> --model <model_name> --gpu <gpu_id>
```

## Acknowledgement
We appreciate the following github repos a lot for their valuable code base or datasets:
1. FourierGNN:https://github.com/aikunyi/FourierGNN
2. StemGNN:https://github.com/microsoft/StemGNN
3. https://github.com/thuml/Time-Series-Library
