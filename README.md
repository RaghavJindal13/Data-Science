# Data-Science
Tutorials, assignments, and competitions from Kaggle and IBM Data Science course.<br><br>
Data Science is what data scientists do. Data Science is nothing but gathering small or big amount of data for analysis.This analysis provides the solution to the problem using appropriate tools. In Data Science you must be curious and have ability of storytelling.Data Scientist is the one providing solution to problems using different tools.<br><br>


A good ,well analysed Report is the one that includes a :<br>
1) Cover Page<br>
2) Table of Contents<br>
3) Executive Summary/abstract section <br>
4) Introduction Section<br>
5) Methodology Section<br>
6) Result Section<br>
7) Discussion + Conclusion Section<br>
8) References Section<br>
9) Acknowledgements Section <br>
10) Appendices Section<br>
<br>
# Importing dataset<br>
Import pandas as pd<br>
•	df=pd.read_csv(data.csv)<br>
•	url = “https//:evliubfukbf”
df=pd.read_csv(url)
•	if headers are not given in dataset
df=pd.read_csv(data.csv,header=None)
headers=[“id”,”name”,”status”]
df.columns=headers<br>
Exporting the dataset<br>
Path=”C:\Windows\download\datascience”
Df.to_csv(path)

<br>
To check shape of dataset – df.shape
To check first 5 rows of dataset—df.head()	df.tail(n)
df.info – gives top 30 and last 30 rows
To check number of rows – len(df)
