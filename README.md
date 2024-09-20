# Comment Safeguard
This project is about Natural Language Processing in which I downloaded the dataset from Kaggle and do after doing data preprocessing apply the Deep Learning Sequential model.
  
# Working:
This the most important to know to we are going to work on this project. So for this let's see how the project will work and steps involved in this project.
 
1. We must have input data that could be comments from different sources with labels. Like, I hate you or I love you.
2. After that we should have labels for these comments that tell us what kind of toxicity comment it was.
3. Convert these comments into Tokens or in vectors like "I love you" the token of this might be [10,400,200] or anything else.
4. Embedding will perform on this after Tokenization. This will convert the vector into again a vector that will look like [1.0,0.5,0.1] for "I", [0.2,0.9,0.5] for 5. "love" and [0.4,0.3,0.9,1.0] for word "you" base on the attributes of the comment.
6. After completing our preprocessing we will pass this embedding vectors to deep neural network that will give us multi-binary outputs that will be checked by our 7. labels and make decision on toxicity.
8. Then save this model into .h5 file and make an app on this model that will Gradio App which is ligt weight to deploy any deep learning model.

# Libraries/Dependencies:

1. Pandas
2. os
3. numpy
4. tensorflow
5. from tensorflow.keras.layers import TextVectorization
6. from tensorflow.keras.models import Sequential
7. from tensorflow.keras.layers import LSTM,Bidirectional,Dense,Dropout,Embedding
8. from tensorflow.keras.metrics import Precision,Recall,CategoricalAccuracy
9. gradio
 
# Steps Involved:
1. Import the Libraries
2. Load the dataset by using Pandas in .csv file.
3. Drop the null values
4. Drop the unwanted columns/features
5. Vectorize the dependent column by using TextVectorization
6. Divide data into x and y
7. Build data pipeline by using tensorflow slices
8. Split the data into train and test
9. Build the model with Bidirectional and Embedding layer
10. Compile and train the model
11. Make some Prediction
12. Evaluate the model
13. Deploy the model on Gradio


# ScreenShots:
![Capture3](https://github.com/whoisusmanali/Comment_Toxicity/assets/104086680/04d3aca4-68f6-4129-89c6-a7b09b0965a6)


![Capture4](https://github.com/whoisusmanali/Comment_Toxicity/assets/104086680/75a329bc-3cc9-4c87-ba0f-6cb358087158)

![Capture5](https://github.com/whoisusmanali/Comment_Toxicity/assets/104086680/3633726c-b855-49ea-9b26-a9fb7039a8a6)

![Capture](https://github.com/whoisusmanali/Comment_Toxicity/assets/104086680/ddcb9565-06f5-4c62-bf3b-c0b1824a2116)

![Capture1](https://github.com/whoisusmanali/Comment_Toxicity/assets/104086680/b2775110-c560-409e-a9d7-bbbbf277902d)

