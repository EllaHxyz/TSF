# Time-series forecasting in stock market

### This is an implementation of different types of Transformers in forecasting NASDAQ index movement. 

This project aims to compare the performance of channel-dependence and channel-independence approach in forecasting stock market movement.  

## Key Designs


:star2: **Channel-independence**: each channel contains a single univariate time series that shares the same embedding and Transformer weights across all the series.

:star2: **Channel-dependence**: fuse channels before Transformers. 

## Results

1. Channel-Independence

2. Channel-dependence


## Getting Started


1. Install requirements. ```pip install -r requirements.txt```

2. data: ./dataset/ixic_all_0613.csv.  

3. Training. Running the scripts are in  ```./run_main.ipynb```. Forecasting results can be found in  ```./test_results/``` and ```./results/```  once the training is done.

You can adjust the hyperparameters based on your needs.

## Acknowledgement

We appreciate the following github repo very much for the valuable code base and datasets:

https://github.com/PatchTST

https://github.com/cure-lab/LTSF-Linear

https://github.com/zhouhaoyi/Informer2020

https://github.com/thuml/Autoformer

https://github.com/MAZiqing/FEDformer

https://github.com/alipay/Pyraformer

https://github.com/ts-kim/RevIN

https://github.com/timeseriesAI/tsai

