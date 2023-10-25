# MLOPS_MLFLOW-



#Machine-Learning-Project-with-MLflow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/PrateekRocks/MLOPS_MLFLOW-
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/PrateekRocks/MLOPS_MLFLOW-.mlflow \
MLFLOW_TRACKING_USERNAME=PrateekRocks \
MLFLOW_TRACKING_PASSWORD=27f5a68da3bcd6d4ca9814bb6d81ae1edfb693f0 \
python script.py

Run this to export as env variables:

```bash

(use set   instead of export in window)
export MLFLOW_TRACKING_URI=https://dagshub.com/PrateekRocks/MLOPS_MLFLOW-.mlflow

export MLFLOW_TRACKING_USERNAME=PrateekRocks

export MLFLOW_TRACKING_PASSWORD=27f5a68da3bcd6d4ca9814bb6d81ae1edfb693f0

```




	





## About MLflow 
MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & tagging your model


