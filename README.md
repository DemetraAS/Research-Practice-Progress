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
- Performed some additional research regarding Turbofan engines and rendered some visualizations for the research paper

Week 6 (April 1st-April 7th 2024):
- Tested Machine Learning algorithms (both classical and ensembles), but the results were once again inappropriate
- During the classification, discovered that the filtering and damage modeling parts were lacking
- Based on the discoveries, improved upon the necessary parts as was seen fit

Week 7 (April 8th-April 14th 2024):
- Created visualizations for the research paper
- Added information to the research paper draft
- Tested the results of the of some suggested models with the new preprocessing

Week 8 (April 15th-April 21th 2024):
- Studied the selection of thresholds for damage modeling
- Concluded that selecting different thresholds for each subset of the NASA C-MAPSS is more appropriate

Week 9 (April 22th-April 28th 2024):
- implemented a restricted Boltzmann Machines and LSTM hybrid architecture from scratch
- the results were underwhelming (not able to achieve state-of-the-art results), so the idea was scrapped
- wrote the theoretical part of the paper

[EASTER BREAK]

Week 10 (May 7th-May 12th 2024):
- changed approaches and decided to implement a CNN-LSTM hybrid architecture
- results were able to achieve state-of-the-art status and were low enough that testing other potential solutions was not warranted
- wrote the part of the paper that describes the methodology of the contribution

Week 11 (May 13th-May 19th 2024):
- implemented other approaches to simply compare the performance metrics
- finalized the first version of the papers by completing the results and conclusions 

Week 12 (May 20th-May 26th 2024):
- edited the research paper and added the final details
