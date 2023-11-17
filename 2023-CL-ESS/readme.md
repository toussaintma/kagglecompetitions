https://www.kaggle.com/competitions/commonlit-evaluate-student-summaries

started: 20230913

20230915 First score 0.5718 as a baseline with a crude deberta-v3-small
0.56751 Using prompts question and title
0.61202 with cross validation
0.6001 from 3 to 5 epochs
0.53524 deberta-v3-large with 2 folds and 3 epochs
0.52544 deberta-v3-small with xgboost on top
0.52103 deberta-v3-large with xgboost on top

Bigger models did help as well as additional input on text quality
