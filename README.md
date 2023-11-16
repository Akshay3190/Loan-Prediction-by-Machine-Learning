# Loan-Prediction-by-Machine-Learning
<br>
Analyzed the data of 614 loan applicants & preiction of  their application ,wether it will get approved or rejected by using Support vector Machine model.
<br>
<br>
Work flow of the project will be as per following-
<br>
<br>
<img width="960" alt="work flow" src="https://github.com/Akshay3190/Loan-Prediction-by-Machine-Learning/assets/149465028/adab0353-da23-48d7-a3b1-299829986896">
<br>
<br>
Libraries we used for the Processing the data-
<br>
<br>
1-Numpy
<br>
2-Pandas
<br>
3-Seaborn
<br>
4-Matplotlib
<br>
<br>
Removed the null values to get ease in analysis.
<br>
<br>
Some columns contains string values & some contains integer (int) values. we need int values for all to analyse the data. Hence we repalce the values of 'Loan Status' like '1' for & '0' for 'n'.
<br>
<br>
Annalysed the data of applicants with factors like their education,marital status,depndents in the family by using bar plots. Categoried it with their loan status for better analysis.
<br>
<br>
Changed the string values of columns like 'Gender','Education','Mariatal status,'Self employed','Property area'.
<br>
<br>
Categorised the data into 2 sectors like 'x' for entire loan data & 'y' for 'loan status' as label.
<br>
<br>
Standardisation of  the data-
<br>
We have data in numeric values & it has a wide range like dependents varying from 0 to 4. Similarly, we have data for ‘Applicant income’,’ Coapplicant income’,’ Loanamount’ in various ranges & the difference is there then it will be difficult for our ML to predict the test data. So overcome it we need to standardized our data in particular range  which will help our ML model to make better predictions.
<br>
We have to standardize data by using the function 'StandardScaler'.
<br>
<br>
Splitting data into train & test-
<br>
<br>
Stratify-
<br>
<br>
The stratify parameter asks whether you want to retain the same proportion of classes in the train and test sets that are found in the entire original dataset. For example, if there are 100 observations in the entire original dataset of which 80 are class a and 20 are class b and you set stratify = True , with a .
<br>
<br>
Random State-
<br>
<br>
If you don't specify the random_state in the code, then every time you run(execute) your code a new random value is generated and the train and test datasets would have different values each time. However, if a fixed value is assigned like random_state = 0 or 1 or 42 or any other integer then no matter how many times you execute your code the result would be the same i.e., the same values in train and test datasets.
<br>
<br>
Running model-Support vector machine-
<br>
<br>
This is supervised learning model. In this, we have to provide data with 2 labels. 1st loan will be approved & another loan will be rejected. Once we train the model it will be trained support vector learning model & we will test the same by giving new data to it.
<br>
<br>
After checking accuracy of both train & test we need the check the implementation of the model with new data.
