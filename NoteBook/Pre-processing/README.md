# # Pre-processing and cleaning: Predicting House Prices

## Contents

- [1. Introduction]
- [2. Removing Outliers]
- [3. Features Engineering]
- [4. Saving our data]

### 1. Introduction

The pre-processing and cleaning is considered as the final step for data manipulation, where we can make sure that:

- No Outliers
- No missing data
- Features Engineering:
  - Engineer New Features if necessary
  - Drop Features
  - Change features structure

### 2. Removing Outliers

Outliers are data points that exist far away from the majority of your data. This can happen due to several reasons, such as incorrect data recording to genuine rare occurrences. Either way you will often want to remove these values as they can negatively impact your models. An example of the negative effect can be seen here where an outlier is causing almost all of the scaled data to be squashed to the lower bound.
