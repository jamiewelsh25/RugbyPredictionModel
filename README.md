# RugbyPredictionModel
Using data from international rugby matches between Tier 1 nations (obtained from https://www.kaggle.com/datasets/lylebegbie/international-rugby-union-results-from-18712022/ ), I build a model to predict the winner of each game as well as a model to predict the points margin.

I use the same methodology the World Rugby rankings to caculate live rankings based on only matches contested between Tier 1 nations (These should mirror very closely the actual rankings) and these rankings are used as explanatory variables for the models along with form over the last five games. Binary indicator varibales are included for cases when the match is held on neutral territory as well as to indicate matches contested at a world cup.

Running the run_models.ipynb notebook will pre-process the data in results.csv and then train and evaluate the machine learning models.


