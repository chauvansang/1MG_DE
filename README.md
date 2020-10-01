NYC TAXI GREEN DATA PREPROCESSING
======

## Requirements to run the notebook

 - This project requires Python 3, scikit-learn, pandas, jupyter-notebook

## Quickstart
1. Clone the repo
> git clone https://github.com/chauvansang/1MG_DE.git
> cd 1MG_DE

2. Start up jupyter using docker
> docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/scipy-notebook
> ##### Then access jupyter at the link http://127.0.0.1:8888/?token=xxxxx provided after running the docker command

3. Open a terminal in the jupyter lab and run
> pip install pyarrow geopy

3. Go to the work folder and run the nyc_data.ipynb file
