# AI-Image-Captioning-Bot-

- Generating Captions for Images

### Steps 
- Data collection
- Understanding the data
- Data Cleaning
- Loading the training set
- Data Preprocessing — Images
- Data Preprocessing — Captions
- Data Preparation using Generator Function
- Word Embeddings
- Model Architecture
- Inference

### Dataset
- You can either download the dataset from kaggle 'flicker8k-dataset' or if you are working on google colab then run following steps
- Go to your kaggle account create new API Token and download the kaggle.json file
- Upload that json file to your google colab and run the commans
- !mkdir ~p ~/.kaggle
- !cp kaggle.json ~/.kaggle/
- !chmod 600 ~/.kaggle/kaggle.json
- !kaggle datasets download -d ming666/flicker8k-dataset and dataset will be downloaded
