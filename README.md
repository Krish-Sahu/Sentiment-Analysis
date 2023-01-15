# Sentiment-Analysis

I have creted a sentiment analysis model, which classifies comments(youtube) into positive and negatives.
To achive this i have pretrained "distilroberta-finetuned-financial-news-sentiment-analysis" transformer
form hugging face using a small dataset downloaded from kaggle.

In datasetprep file i have removed data imbalance,split the data into test and train and uploaded the 
data to hugging face repository.
Data can be accessed at "DepositorOP/masterstack" on Hugging Face.

In fine tuning the transformer has been fintuned using the above data.
Following libraries were used datasets, Transformers from hugging face.
Final model was again uploaded on huging face for easy access.

The model file just utilises the above model and classifies the comments.
The model can be accessed at "DepositorOP/Finituned-bert".
