# Research-Practice-Progress

Week 1 (February 26th-March 3rd 2024):

- Tested our best GRU architecture on the existing dataset, without preprocessing (proved not to be particularly useful)
- Identified a particularly promising and novel solution, i.e. a Restricted Boltzmann Machines-GRU hybrid

Week 2 (March 4th-March 10th 2024):

- Started the implementation by constructing our dataframe from the 3 separate files (proved a bit challenging)
- Conducted a correlation analysis to assess which attributes can be excluded from each subset
- Applied Moving Median Filtering to deal with noise and outliers (window_size=5) 
- Performed Z-score normalization (standardization)
- Implemented the calculation of the asymmetric scoring function (PHME- Prognostic Health Management Error)

Week 3 (March 11th-March 17th 2024):
- Discovered that the previous assignation of the target label (RUL) was not properly conducted
- Implemented a piece-wise function able to estimate the first point of degradation for every engine that has been run to failure
- Performed an Exploratory Data Analysis for each individual attribute and dataset (an univariate analysis complete with all the necessary statistics)
- Attempted to correctly assign the RUL labels to the attributes, based on the degradation modeling step (still in progress)
  
Week 4 (March 18th-March 24th 2024):
- Managed to accurately assign RUL to the training and testing sets (assignation is different for testing and training)
- Created a draft for the research paper, making sure that the length criteria will be respected

Week 5 (March 25th-March 31th 2024):
- Prepared the preprocessed data for training
- Established the performance metrics that will be used - RMSE, MAPE, MAE and the asymmetric scoring function
- Started testing a variety of suggested architectures, but the performance metrics were deeply unsatisfactory (with and without preprocessing)
- Tried to pinpoint the issue, but was unable to do so

Week 6 (April 1st-April 7th 2024):

Week 7 (April 8th-April 14th 2024):

Week 8 (April 15th-April 21th 2024):

Week 9:

Week 10:

Week 11:

Week 12:
