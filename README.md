# Intrusion-Detection-System-Using-Machine-Learning

## Implementation 
### Dataset 
CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
* Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html  
* For the purpose of displaying the experimental results in Jupyter Notebook, the sampled subsets of CICIDS2017 is used in the sample code. The subsets are in the "data" folder.

CAN-intrusion dataset, a benchmark network security dataset for intra-vehicle intrusion detection
* Publicly available at: https://ocslab.hksecurity.net/Datasets/CAN-intrusion-dataset  
* Can be processed using the same code

### Code  
* [Tree-based_IDS_GlobeCom19.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning/blob/main/Tree-based_IDS_GlobeCom19.ipynb): code for the paper "Tree-Based Intelligent Intrusion Detection System in Internet of Vehicles"  
* [MTH_IDS_IoTJ.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning/blob/main/MTH_IDS_IoTJ.ipynb): code for the paper "MTH-IDS: A Multi-Tiered Hybrid Intrusion Detection System for Internet of Vehicles"  
* [LCCDE_IDS_GlobeCom22.ipynb](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning/blob/main/LCCDE_IDS_GlobeCom22.ipynb): code for the paper "LCCDE: A Decision-Based Ensemble Framework for Intrusion Detection in The Internet of Vehicles"  

### Machine Learning Algorithms  
* Decision tree (DT)
* Random forest (RF)
* Extra trees (ET)
* XGBoost  
* LightGBM  
* CatBoost  
* Stacking
* K-means

### Hyperparameter Optimization Methods  
* Bayesian Optimization with Gaussian Processes (BO-GP)
* Bayesian Optimization with Tree-structured Parzen Estimator (BO-TPE)  

### Requirements & Libraries  
* Python 3.6+ 
* [scikit-learn](https://scikit-learn.org/stable/)  
* [Xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [lightgbm](https://lightgbm.readthedocs.io/en/v3.3.2/Python-Intro.html)
* [catboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [FCBF](https://github.com/SantiagoEG/FCBF_module)
* [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize)  
* [hyperopt](https://github.com/hyperopt/hyperopt)   
* [River](https://riverml.xyz/dev/)  



