# tfx-dv

## About

This is an experimental repo for data validation with TensorFlow Extended.

Work in progress.

## How to use

Create and activate environment:
```
conda env create -f ~/tfx-dv/datavalid.yaml
conda activate datavalid
```

Start Jupyter and run the notebook:
```
export KERAS_BACKEND=tensorflow MEM_LIMIT=100000000; jupyter notebook --port=8888 --ip=0.0.0.0
```

MEM_LIMIT is not enforced, only for reference purposes.