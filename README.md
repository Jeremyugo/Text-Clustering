## Text-Clustering

In this repository we perform an unsupervised machine learning task by clustering the BBC News dataset based on their content. The dataset, as you will see has a news category feature which will serve as a metric for evaluating our model performance at the end, in addition to the SilhouetteScore.

2 techniques were used:
- TextVectorization to map strings to integer indices
- Pre-trained encoder model to generate embeddings

In summary, by using a pre-trained Universal encoder, my Kmeans model was able to predict cluster labels which matched the news category with a 96% accuracy!

### Model performance

![image](https://github.com/Jeremyugo/Text-Clustering/assets/36512525/511f9655-3d53-466a-ba2e-e0fa3144ab4b)

![image](https://github.com/Jeremyugo/Text-Clustering/assets/36512525/0a904760-fca5-4013-8bc6-93b872a5d75f)

![image](https://github.com/Jeremyugo/Text-Clustering/assets/36512525/78982497-dc52-4ced-a848-2fb2b7593ef1)
