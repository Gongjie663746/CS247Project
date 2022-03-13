# CS247Project

Data processing pipeline: 
1. run `data_extraction.ipynb` to extract dataframe from raw data. 
2. run `Filtering.ipynb` to see the statistics of the data and perform upper thresholding and min-support recursive to balance the data. 
3. [OPTIONAL] to apply clustering to the dataset, run `Clustering.ipynb` to generate the clustered version of the data. 
4. run `data_formatting.ipynb` to split the training and testing data, and generate the lines of model input. 


Model training: 
1. Run `LightGCN.ipynb` to run the baseline model. 
2. Run `LightGCN_with_text_embed_init.ipynb` to run the model with text_embedding initialization. 
