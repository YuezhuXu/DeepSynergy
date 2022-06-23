# DeepSynergy

Cell line embeddings are attained by finding highly variable features (500) and applying pca (12&30) based on the elbow plot. Essential preprocessing like scaling and normalization follows Seurat PCA (see code). 15 Drugs embedding for two and cell line embedding are concatnated. These are included in preprocessing.ipynb. The result is stored as X_15_emb_c*.p in dataset. (output for original embeddings is X_15.p)

Data split for train, test and validation set is done with data_split.ipynb and the result is stored as data_15(_emb_c*)_testfold0.p' (input) in dataset.

DeepSynergy is executed in DeepSynergy.ipynb and the model is stored as my_model_15(_emb_c*).h5

Performance are concluded in performance.ipynb
