# DATA ANALYSIS PROJECT WITH PYTHON ON SCHOOLS SAT SCORES DATA
A DATA SCIENCE PROJECT WITH PYTHON
![New York City schoolbus](schoolbus.jpg)

Photo by [Jannis Lucas](https://unsplash.com/@jannis_lucas) on [Unsplash](https://unsplash.com).
<br>

Every year, American high school students take SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. There are three sections - reading, math, and writing, each with a **maximum score of 800 points**. These tests are extremely important for students and colleges, as they play a pivotal role in the admissions process.

Analyzing the performance of schools is important for a variety of stakeholders, including policy and education professionals, researchers, government, and even parents considering which school their children should attend. 

We have been provided with a dataset called `schools.csv`, which is previewed below.

Our aim is to answer three key questions about New York City (NYC) public school SAT performance:
- Which NYC schools have the best math results? Atleast 80%
- What are the top 10 performing schools based on the combined SAT scores?
- Which single borough has the largest standard deviation in the combined SAT score?

# Skills employed and Methods used:
- Pandas Library: This code utilizes the Pandas library extensively for data manipulation and analysis.

- pd.read_csv(): This method from the Pandas library is used to read data from a CSV file into a DataFrame.

- head(): This Pandas DataFrame method is used to display the first few rows of the DataFrame.

- DataFrame Indexing and Selection: Square brackets ([]) are used to select specific columns from the DataFrame.

- Boolean Indexing: This is used to filter rows based on certain conditions, as seen in schools['average_math'] >= (0.8*800).

- sort_values(): This method is used to sort the DataFrame based on specified column(s), both ascending or descending.

- Mathematical Operations: Mathematical operations are performed to calculate the total SAT score by adding individual SAT scores.

- Aggregation with groupby(): The groupby() method is used to group data based on a certain criterion, followed by aggregation functions like agg() to compute statistics (count, mean, standard deviation) for each group.

- round(): This method is used to round off the numerical values to a specified number of decimals.

- Method Chaining: Multiple methods are chained together, allowing for concise and efficient code structure.

- DataFrame Manipulation: Columns are renamed and indexes are reset for better clarity and presentation.

- Conditional Filtering: The code uses conditions to filter data based on certain criteria, such as finding schools with math results above 80% or identifying the borough with the largest standard deviation.

- Statistical Analysis: Standard deviation is used as a measure of dispersion to analyze the variability of SAT scores within different boroughs.
