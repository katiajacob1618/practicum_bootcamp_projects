# 9th Project for Practicum Bootcamp
## Maching Learning Model to Predict Amount of Gold Recovered from Gold Ore for Zyfra 
### Description:
The goal of this project is to build a machine learning project to predict the amount of gold recovered from gold ore, for Zyfra who develops efficiency solutions for mining, oil & gas, chemical and engineering industries.
We have data on extraction and purification, stored in three files, a training dataset, a test dataset, and the original source dataset.
This project consists of data preprocessing, exploratory data analysis, evaluation and training of different machine learning models to predict amount of gold extracted from mined ore after going through several purification stages, and selection of best model. The targets are *rougher.output.recovery* and *final.output.recovery*. The metric used is here is symmetric Mean Absolute Percentage Error.

### Data:
We are given three different files:

- `gold_recovery_train.csv` — consists of 87 variables, part of the full dataset reserved for training
- `gold_recovery_test.csv` — consists of 53 variables, part of the dataset reserved for testing
- `gold_recovery_full.csv` — consists of 87 variables, full dataset
  - *date* 
  - *final.output.concentrate_ag* 
  - *final.output.concentrate_pb*
  - *final.output.concentrate_sol* 
  - *final.output.concentrate_au* 
  - *final.output.recovery* 
  - *final.output.tail_ag* 
  - *final.output.tail_pb*
  - *final.output.tail_sol*
  - *final.output.tail_au*
  - *primary_cleaner.input.sulfate*
  - *primary_cleaner.input.depressant* 
  - *primary_cleaner.input.feed_size* 
  - *primary_cleaner.input.xanthate* 
  - *primary_cleaner.output.concentrate_ag* 
  - *primary_cleaner.output.concentrate_pb* 
  - *primary_cleaner.output.concentrate_sol* 
  - *primary_cleaner.output.concentrate_au* 
  - *primary_cleaner.output.tail_ag* 
  - *primary_cleaner.output.tail_pb* 
  - **...**
 
### Libraries used:
pandas, 
numpy, 
sidetable,
matplotlib,
scipy,
sklearn, 
