### AI BASED SOCIAL MEDIA MONITORING
#### AUTHOR : VAISHNAV KRISHNA P

### DATASET - TOXIC COMMENT DETECTION
- Dataset is taken from :  [Kaggle](https://www.kaggle.com/datasets/julian3833/jigsaw-toxic-comment-classification-challenge?select=train.csv).
- Dataset Licence :  CC0: Public Domain
- Owner : Julián Peller
- Since dataset is very large in size(>100mb) not available in this repo.
  
### Problem Statement
- In today’s digital world, the internet is flooded with toxic comments and misleading posts.
This is a humble attempt to develop an AI model that can detect such harmful content early, helping prevent the spread of misinformation.
- The model leverages NLP (Natural Language Processing) techniques to identify toxicity in posts and protect users from its impact.

### MODEL 1 DATA PREPROCESSING(TOXIC COMMENT DETECTION)
- Data preprocessing techniques used for this model.
1. Converting all text to lower case(python)
2. Autocorrect(Speller) model to correct the spelling
3. Tokenization(nltk)
4. Removing all the numbers, special charectors, punctation marks(using Regular expression)
5. Stopwords(nltk)
6. WordNetLemmatizer model(Lematizer) : to get the root of the words.

### ACCURACY : 90.54 (First - simple approach)
[NOTE BOOK](https://www.kaggle.com/code/vaishnavkrishnap/toxic-comment-classifier-90-accuracy)
   
- Note : Used jupyter notebook so, computationally very hard so, have to do it in colab and save the clean text for the further model generation.
