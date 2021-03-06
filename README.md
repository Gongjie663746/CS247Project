# CS247Project
Link to the MemeTracker dataset:
http://snap.stanford.edu/memetracker/

Data processing pipeline: 
1. run `data_extraction.ipynb` to extract dataframe from raw data. 
2. run `Filtering.ipynb` to see the statistics of the data and perform upper thresholding and min-support recursive to balance the data. 
3. [OPTIONAL] to apply clustering to the dataset, run `Clustering.ipynb` to generate the clustered version of the data. 
4. run `data_formatting.ipynb` to split the training and testing data, and generate the lines of model input. 


Model training: 
1. Run `LightGCN.ipynb` to run the baseline model. 
2. Run `LightGCN_with_text_embed_init.ipynb` to run the model with text_embedding initialization. 
3. Run `LightGCN_with_clustering.ipynb` to run the model with clustering data. 

Tips: \
To change directory of training and testing data, go to `dataloader.py` block to change the directories. \
Note that the test batch needs to be not more than 1/10 of the user. It can be set in the Parsing block. \
Note that some dependencies requires you to restart the runtime to be funtioning. Make sure all the code block and dependencies are loaded when you run. 
