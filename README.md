# MultilingualEmojiPrediction
We build multilingual models to predict emojis for tweets written in English and Spanish.

Here we tackle two subtasks
1. Emoji Prediction in English 
2. Emoji Prediction in Spanish

Main Reference paper for this task:

Barbieri, Francesco and Camacho-Collados, Jose and Ronzano, Francesco and Espinosa-Anke, Luis and Ballesteros, Miguel and Basile, Valerio and Patti, Viviana and Saggion, Horacio (2018) 
SemEval-2018 Task 2: Multilingual Emoji Prediction (https://aclanthology.org/S18-1003/), 
Proceedings of the 12th International Workshop on Semantic Evaluation (SemEval-2018)

Training and Evaluation Data: The data for the task will consist of 500k tweets in English and 100K tweets in Spanish. The tweets were retrieved with the Twitter APIs, from October 2015 to February 2017, and geolocalized in the United States and Spain. The dataset includes tweets that contain one and only one emoji, of the 20 most frequent emojis. Data will be split into trial, training, and test.

Label set: As labels, we will use the 20 most frequent emojis of each language. They are different across the English and Spanish corpora. In the following, we show the distribution of the emojis for each language (numbers refer to the percentage of occurrence of each emoji).


The links the datasets are in the following folder: https://drive.google.com/drive/folders/1bFsKK37oYAn6VXfpS08hH7CgVqpfLPp1?usp=sharing


More task description can be found here: 

@InProceedings{semeval2018task2,
  title={{SemEval-2018 Task 2: Multilingual Emoji Prediction}},
  author={Barbieri, Francesco and Camacho-Collados, Jose and Ronzano, Francesco and Espinosa-Anke, Luis and Ballesteros, Miguel and Basile, Valerio and Patti, Viviana and Saggion, Horacio},
  booktitle={Proceedings of the 12th International Workshop on Semantic Evaluation (SemEval-2018)},
  year={2018}, 
  address={New Orleans, LA, United States},
  publisher = {Association for Computational Linguistics}
 } 
