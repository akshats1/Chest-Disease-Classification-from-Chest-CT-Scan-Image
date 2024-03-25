# Chest-Disease-Classification-from-Chest-CT-Scan-Image [![Trigger Jenkins Job](https://github.com/akshats1/Chest-Disease-Classification-from-Chest-CT-Scan-Image/actions/workflows/main.yaml/badge.svg)](https://github.com/akshats1/Chest-Disease-Classification-from-Chest-CT-Scan-Image/actions/workflows/main.yaml)
LINK:
[link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view)

## Workflows
1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

## How to Run
```bash
conda create -n chest python=3.8 -y
```
```bash
conda activate chest
```
```bash
pip install -r requirements.txt
```
## Mlflow dagshub connection uri
```bash
MLFLOW_TRACKING_URI=https://dagshub.com/akshats1/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow \
MLFLOW_TRACKING_USERNAME=akshats1 \
MLFLOW_TRACKING_PASSWORD=b22094290eabd85478c1d26cbd09b0082f13954e \
python script.py
```
## RUN from bash terminal
```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/akshats1/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow \
export MLFLOW_TRACKING_USERNAME=akshats1 \
export MLFLOW_TRACKING_PASSWORD=b22094290eabd85478c1d26cbd09b0082f13954e 

```
## DVC cmd
``` bash
dvc init
dvc repro
dvc dag
```
