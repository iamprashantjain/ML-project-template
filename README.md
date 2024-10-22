# used-card-price-prediction-mlops

### steps
1. create github repo & clone it in local pc
2. create template.py file to create folder/file structure
3. .github/workflows is for CI/CD
4. experiments & ipynb file is for experiments with data
5. "src" is the main folder --> components are the steps we will perform on data like data gathering, feature engineering, model building & evaluation --> all these steps altogether become the training pipeline
6. exception & logger where we write exception.py & logging.py codes
7. pipeline: where write pipeline codes which are set of components
8. utils: where we write common functions to be used in the project