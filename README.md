# MLOps Final Project: Instacart Reorder Prediction

## 1. Project setup
``` basg
git clone https://github.com/anhndq01/MLOps_Final_Instacart_Reorder_Prediction.git
cd MLOps_Final_Instacart_Reorder_Prediction
```

## 2. How to get data

### Install DVC
``` bash
pip install dvc
```

### Set up Google Drive for syncing

1. Install Google Drive for Desktop and sign in to your account.
2. Choose Mirror files mode in the preferences.
3. Create or pick a folder to be used for this project, e.g.:
   /Users/your_user_name/Google Drive/Synced

### Configure DVC
``` bash
dvc remote add -d gdrive_local "/Users/your_user_name/Google Drive/Synced" --local
```

### Pull the datasets
``` bash
dvc pull
```

After this, verify that the data/ folder appears in your local project folder.
