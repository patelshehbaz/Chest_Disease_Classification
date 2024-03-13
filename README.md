# Chest_Disease_Classification

### Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components6.
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

How to run?

```
conda create -n chest python=3.8 -y
```

```
conda activate chest
```

```
pip install -r requirements.txt
```

```
python app.py
```

### Mlflow dagshub connection uri

```
MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/mlflow-experiment-demo.mlflow \
MLFLOW_TRACKING_USERNAME=patelshehbaz \
MLFLOW_TRACKING_PASSWORD=480d774605de403539ede34b17f4416d239022c4 \
python script.py
```

### Run from bash terminal

```
export MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/mlflow-experiment-demo.mlflow
```

```
export MLFLOW_TRACKING_USERNAME=patelshehbaz
```

```
export MLFLOW_TRACKING_PASSWORD=480d774605de403539ede34b17f4416d239022c4
```
