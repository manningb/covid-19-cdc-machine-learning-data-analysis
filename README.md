In this main directory you will find the following:
	- 1_Homework1: This contains my corrections from Homework 1, I have added in a number of new features here which are then used throughout Homework 2.
	Most of this file is same apart from the very last section where the new features are added and evaluated using correlation coefficients
	- 2_Homework2: This contains my work for Homework 2.
		- data: 
			- covid19-cdc-17324576-clean-new-features.csv  - Used from the start of Homework 2 to test Linear Regression, Logistic Regression and Random Forests
			- covid19-cdc-17324576-for-part-5.csv - Used for Part 5 to evaluate if more features would be better - it does not contain the feature scaling for time since start used in the above dataset
			- 24032021-covid19-cdc-deathyn-recent-10k.csv - New dataset for testing part 5
		- trees: Contains various tree files for presentation in the notebook.
		- confusion_matrix.py: This was adapted from code found online to quickly generate a confusion matrix and metrics based on predicted and actual data
		- 2_2020-Homework2-Notebook.ipynb: Homework 2 notebook
		- pickle: Pickle Randomised Search results