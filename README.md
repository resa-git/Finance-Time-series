# Finance-Time-series
## Docker
The jupyter notebook is run in docker. In order to setup docker, the follwoing commands are required
1 - docker pull jupyter/r-notebook
2 - in the current folder type mkdir wvol
3 - docker run  --rm -it -p 8888:8888  --gpus all -v "$(pwd)"/wvol:/home/jovyan/work styleclip:latest /bin/bash
4 - in the container, go to the work directory and type jupyter lab

## Garch Models
Understanding and analyzing the underlying mechanism of the stock price was always one of the major objectives among traders and hedge-fund companies. The non-constant volatility of the stock returns demands special models to predict the stock price characteristics. This report analyzes the underlying price evolution of the S&P 500 index and forecasts the volatility and the return. In particular, we discuss the performance of a special model called Generalized AutoRegressive Conditional Heteroskedasticity (GARCH)
