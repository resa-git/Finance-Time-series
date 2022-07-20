# Finance-Time-series
## Docker
The jupyter lab is run in the docker. In order to setup the docker, please follow these steps:
1. In the current folder type docker pull jupyter/r-notebook
2. In the current folder type mkdir wvol
3. In the current folder docker run  --rm -it -p 8888:8888  --gpus all -v "$(pwd)"/wvol:/home/jovyan/work styleclip:latest /bin/bash
4. In the container, go to the work directory and type jupyter lab

## Garch Models
Understanding and analyzing the underlying mechanism of the stock price was always one of the major objectives among traders and hedge-fund companies. The non-constant volatility of the stock returns demands special models to predict the stock price characteristics. This report analyzes the underlying price evolution of the S&P 500 index and forecasts the volatility and the return. In particular, we discuss the performance of a special model called Generalized AutoRegressive Conditional Heteroskedasticity (GARCH)
