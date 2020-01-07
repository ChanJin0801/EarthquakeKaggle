# EarthquakeKaggle

This kaggle project predicts the time remaining before laboratory earthquakes occur from real-time seismic data. 

The first model is CatBoostRegressor(submission1.csv).\
The second model is SVM + kernel(submission2.csv).\
The last try is CatBoostRegressor + GridCV(submissionGrid, submissionGrid2.csv, submissionGrid3.csv).\

The last try got the best public score on Kaggle, but it takes so much time for GridCV.\
So the most efficient model seems like SVM + kernel.

<img width="795" alt="Screen Shot 2020-01-07 at 10 30 03 AM" src="https://user-images.githubusercontent.com/40285946/71861665-704a4080-313a-11ea-8d7b-e47fe2ed25f7.png">
