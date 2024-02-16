# Experiment - 2 : Apply data cleaning techniques (e.g. Data Imputation).

## Datasets:
- CUSTOMER SEGMENTATION
- FRAUD DETECTION
- House Price Prediction
- Product Recommendation
- Stock Price Prediction
- Weather Prediction

## TOOLS : R, PYTHON 

## What is data cleaning?
- the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset.
- the process that removes data that does not belong in your dataset. 

## How to clean data
- Step 1: Remove duplicate or irrelevant observations
- Step 2: Fix structural errors
- Step 3: Filter unwanted outliers
- Step 4: Handle missing data(Data Imputation)

## Some Data Imputation techniques:
### 1. Next or Previous Value
- For time-series data or ordered data, there are specific imputation techniques.
- These techniques take into consideration the dataset's sorted structure, wherein nearby values are likely more comparable than far-off ones.
- The next or previous value inside the time series is typically substituted for the missing value as part of a common method for imputed incomplete data in the time series.
- This strategy is effective for both nominal and numerical values.

### 2. K Nearest Neighbors
- The objective is to find the k nearest examples in the data where the value in the relevant feature is not absent and then substitute the value of the feature that occurs most frequently in the group.

### 3. Maximum or Minimum Value
- You can use the minimum or maximum of the range as the replacement cost for missing values if you are aware that the data must fit within a specific range [minimum, maximum] and if you are aware from the process of data collection that the measurement instrument stops recording and the message saturates further than one of such boundaries.
- For instance, if a price cap has been reached in a financial exchange and the exchange procedure has indeed been halted, the missing price can be substituted with the exchange boundary's minimum value.

### 4. Missing Value Prediction
- Using a machine learning model to determine the final imputation value for characteristic x based on other features is another popular method for single imputation.
- The model is trained using the values in the remaining columns, and the rows in feature x without missing values are utilized as the training set. 
- Depending on the type of feature, we can employ any regression or classification model in this situation.
- In resistance training, the algorithm is used to forecast the most likely value of each missing value in all samples.
- A basic imputation approach, such as the mean value, is used to temporarily impute all missing values when there is missing data in more than a feature field.
- Then, one column's values are restored to missing. After training, the model is used to complete the missing variables.
- In this manner, an is trained for every feature that has a missing value up until a model can impute all of the missing values.

### 5. Most Frequent Value
- The most frequent value in the column is used to replace the missing values in another popular technique that is effective for both nominal and numerical features.

### 6. Average or Linear Interpolation
- The average or linear interpolation, which calculates between the previous and next accessible value and substitutes the missing value, is similar to the previous/next value imputation but only applicable to numerical data.
- Of course, as with other operations on ordered data, it is crucial to accurately sort the data in advance, for example, in the case of time series data, according to a timestamp.

### 7. (Rounded) Mean or Moving Average or Median Value
- Median, Mean, or rounded mean are further popular imputation techniques for numerical features. The technique, in this instance, replaces the null values with mean, rounded mean, or median values determined for that feature across the whole dataset. It is advised to utilize the median rather than the mean when your dataset has a significant number of outliers.

### 8. Fixed Value
- Fixed value imputation is a universal technique that replaces the null data with a fixed value and is applicable to all data types.
- You can impute the null values in a survey using "not answered" as an example of using fixed imputation on nominal features.
- Since we have explored single imputation, its importance, and its techniques, let us now learn about Multiple imputations.
