## wids2022

Women in Data Science aims to encourage and inspire women in the data science field and to stimulate more gender diversity. Each year, WiDS hosts a machine learning datathon focused on a social impact challenge.

This year’s datathon focused on climate change. Climate change is a globally relevant, urgent, and multi-faceted issue heavily impacted by energy policy and infrastructure. Addressing climate change involves mitigation (i.e. mitigating greenhouse gas emissions) and adaptation (i.e. preparing for unavoidable consequences). 

The aim of the datathon is to predict building energy consumption using variables that describe building characteristics and climate and water variables for the regions in which the buildings are located. Accurate predictions of energy consumption can help policymakers target retrofitting efforts to maximize emissions reductions. Click [here](https://www.kaggle.com/c/widsdatathon2022) to view the competition page on Kaggle.

For this competition, I collaborated with Meyke Bos in team Techonistas. We won the WiDS Maastricht datathon and obtained a top 7% score (rank 57) in the global competition with a RMSE of 21.502


## Competition files
- [EDA](https://github.com/BrendaLoznik/wids2022/blob/main/1_EDA.ipynb): Data exploration using data quality reports and visualizations
- [Data cleaning](https://github.com/BrendaLoznik/wids2022/blob/main/2_Data_Cleaning.ipynb): Dealing with missing data
- [Feature engineering](https://github.com/BrendaLoznik/wids2022/blob/main/3_Feature_Engineering.ipynb): Creating building id’s and other features
- [Feature selection](https://github.com/BrendaLoznik/wids2022/blob/main/4_Feature_Selection.ipynb): Using VIFs to create feature sets
- [Modelling](https://github.com/BrendaLoznik/wids2022/blob/main/5_Modelling.ipynb): Using a weighted voting regressor with a tuned random forest and XGBoost

# Bonus
- [Adversarial validation](https://github.com/BrendaLoznik/wids2022/blob/main/6_Adversaerial_Validation.ipynb): What features are very different between the train and test set?
- [Cross validation](https://github.com/BrendaLoznik/wids2022/blob/main/7_Cross_validation_Timeseries.ipynb): Using a rolling and sliding window during cross validation.
