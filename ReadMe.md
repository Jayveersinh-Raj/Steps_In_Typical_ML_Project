Steps for building any ML/DL model
 1. Import the data
 2. Preprocessing the data if required
 3. Analysing the data to create an insight
 4. Dropping irrelevant features 
 5. Splitting test and train set (stratified if necessary) using *sklearn.model_selection import StratifiedShuffleSplit*
 
 if no stratification required, one can use *sklearn.model_selection import train_test_split*
 
 6. Visualise the data
 7. From the ananlysis above, it is time to select appropiate model
