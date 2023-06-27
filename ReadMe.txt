__________Stages__________

* Stage 1: Create Abstract
	- Pick a theme
	- Find a dataset
	- Create abstract

* Stage 2: Exploratory Data Analysis
	- Create Exploratory Data Analysis

* Stage 3: Initial Model Development
	- Develop the initial models, get feedback from instructor

* Stage 4: Revised Model Development
	- Edit models based on feedback, replace models if necessary

* Stage 5: Create Writeup of Research
	- Use model evaluation metrics to evaluate which model is best at predicting stock data
	- Use model evaluation metrics to evaluate which model is best at predicting stock data during the COVID pandemic

* Stage 6: Research Presentation
	- Create research presentation
	- Present research


__________Contents__________

* Exploratory Data Analysis.ipynb
	- Explores the key attributes of the dataset
	- Converts the Date column to a DateTime Objects for visuals
	- Explores basic information about the key attributes
	- Displays boxplots and lineplots of the key attributes
	- Displays correlation matrix of the key attributes
	- Saves the key attribute data to a new dataset for analysis

* Prophet.ipynb
	- Imports the attributes dataset
	- Formats the Date to fit modelling requirements
	- Has a function to generate model evaluation metrics
	- Splits the dataset into training and testing sets
	- Splits the dataset into precovid (training) and covid (testing) sets
	- Runs the model on the training and testing sets, displays linegraphs and evaluates the model
	- Runs the model on the precovid (training) and covid (testing) sets, displays linegraphs with both the testing and model created prediction sets and evaluates the model
	- Displays the evaluation metrics for each model

* ARIMA.ipynb
	- Imports the attributes dataset
	- Formats the Date to fit modelling requirements
	- Has a function to generate model evaluation metrics
	- Splits the dataset into training and testing sets
	- Splits the dataset into precovid (training) and covid (testing) sets
	- Runs the model on the training and testing sets, displays linegraphs and evaluates the model
	- Runs the model on the precovid (training) and covid (testing) sets, displays linegraphs with both the testing and model created prediction sets and evaluates the model
		> It appears that there is some sort of issue with my first set of predictions, this occurred on my final run before uploading so I need to investigate why the prediction values have changed
	- Displays the evaluation metrics for each model

* SARIMA.ipynb
	- Imports the attributes dataset
	- Formats the Date to fit modelling requirements
	- Has a function to generate model evaluation metrics
	- Splits the dataset into training and testing sets
	- Splits the dataset into precovid (training) and covid (testing) sets
	- Development to train the dataset is in progress however I am currently unable to run the model as I cannot find the seasonal order values needed. Additionally, I had issues running the model in earlier versions of the code as I was running out of RAM (I have 16gb installed) which I may need to resolve as well.

* DeepAR.ipynb
	- Imports the attributes dataset
	- Formats the Date to fit modelling requirements
	- Has a function to generate model evaluation metrics
	- Splits the dataset into training and testing sets
	- Splits the dataset into precovid (training) and covid (testing) sets
	- Development to train the dataset is in progress however I am currently unable to run the model

* Exploratory Data Analysis.html
	- HTML Export of the Exploratory Data Analysis.ipynb file

* Prophet.html
	- HTML Export of the Prophet.ipynb file

* ARIMA.html
	- HTML Export of the ARIMA.ipynb file

* SARIMA.html
	- HTML Export of the SARIMA.ipynb file

* DeepAR.html
	- HTML Export of the DeepAR.ipynb file

* DIS.csv
	- Original dataset

* dataset.csv
	- Dataset generated as a part of the Exploratory Data Analysis