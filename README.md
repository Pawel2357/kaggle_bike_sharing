# Kaggle bike sharing

The repository contains scripts training xgboost model for kaggle bike sharing competition.


## Files structure
- **initial_preprocessing.ipynb** - notebook with scripts for initial data preprocessing
- **train_xgboost.ipynb** - notebook with scripts for xgboost model training
- **Dockrefile** - contain all command to create docker container ready to run jupyter notebooks with solutions


## How to run scripts in docker?
    cd code_repository
    docker build -t xgboost_test .
    docker run -it <path_to_repo>:<path_inside_container> -p 8888:8888 xgboost_test bash
    jupyter-notebook --ip=0.0.0.0 --no-browser --allow-root

## Results

Final kaggle score: 0.40737
298 #
