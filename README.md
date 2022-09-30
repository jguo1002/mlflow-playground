# mlflow-playground
Learn how to use mlflow

## Get Started

```sh
python3 -m venv .mlflow
source .mlflow/bin/activate
pip install -r requirements.txt 
```

## Clone Examples 

```sh
git clone \
  --depth 1  \
  --filter=blob:none  \
  --sparse \
  https://github.com/mlflow/mlflow \

cd mlflow
git sparse-checkout set examples
```

[sparse-checkout](https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/52269934#52269934)

## Tracking UI

```sh
# port number below 5000 works
mlflow ui -p 4242
```