# Dataset Access Instructions

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/xiaojiu1414/digix-global-ai-challenge

Due to size constraints, the raw dataset is not included in this repository.

## Downloading the Dataset Using the Kaggle API

1. Create a Kaggle account if you do not already have one.
2. Navigate to your Kaggle account settings and generate an API token.
3. Download the `kaggle.json` file.
4. Place the file in the following directory on your machine:

   ~/.kaggle/kaggle.json

5. Set the correct file permissions:

   chmod 600 ~/.kaggle/kaggle.json

6. Install the Kaggle API if needed:

   pip install kaggle

7. Download the dataset using the command:

   kaggle datasets download xiaojiu1414/digix-global-ai-challenge

8. Unzip the dataset and place the files in the `data/` directory or update notebook paths accordingly.

## Notes

The notebooks in this repository assume the dataset is either stored locally or cached using joblib to avoid repeated downloads.
