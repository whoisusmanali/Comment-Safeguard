# Comment_Toxicity
This project is about Natural Language Processing in which I downloaded the dataset from Kaggle and do after doing data preprocessing apply the Deep Learning Sequential model.

# Working:
This the most important to know to we are going to work on this project. So for this let's see how the project will work and steps involved in this project.
 
1. We must have input data that could be comments from different sources with labels. Like, I hate you or I love you.
2. After that we should have labels for these comments that tell us what kind of toxicity comment it was.
3. Convert these comments into Tokens or in vectors like "I love you" the token of this might be [10,400,200] or anything else.
4. Embedding will perform on this after Tokenization. This will convert the vector into again a vector that will look like [1.0,0.5,0.1] for "I", [0.2,0.9,0.5] for 5. "love" and [0.4,0.3,0.9,1.0] for word "you" base on the attributes of the comment.
6. After completing our preprocessing we will pass this embedding vectors to deep neural network that will give us multi-binary outputs that will be checked by our 7. labels and make decision on toxicity.
8. Then save this model into .h5 file and make an app on this model that will Gradio App which is ligt weight to deploy any deep learning model.

