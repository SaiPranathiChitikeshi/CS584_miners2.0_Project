# Student Mental health Prediction

To run the project, clone the repository or download the zip file and extract the dataset folders and then execute ipynb file.
For executing ipynb file, you can use Jupyter Notebook or any other ipynb platform

Data analysis to provide insights in order to find solutions to the problem of depression and suicide, especially in university students.
There are 2 ipynp files in this project.

The year_wise_suicide_analysis.ipynb is used for analyzing the data for a period of time. We collected data from different years to analyze the suicide rate of the students. 
The miners2.0.ipynb file is the main program file.

Two datasets i.e., general characteristics and HADS are used to get the predictions 

General characteristic data set had different dataset files with different characters 
The HADS dataset has different dataset files for different questions.

These datasets are combined into a single data frame and the prepossessing is done.
With the help of the HADS dataset HADS score was found and added which helps in knowing a person’s mental health.
With the help of the general characteristics, BMI is calculated and added.

Then Preprocessing of data was done by removing the missing values and feature selection.
After scaling the data, it was split it into training and testing then the different classification models were applied to find the best model.
From the data different parameter analyses such as Gender, peer pressure, exercise, and BMI was observed and plotted.

