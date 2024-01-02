# web-scrapping-challenge

This challenge was devided into two parts. In part one, we used beautiful soup to extract the titles and preview texts from the mars news website and stored the data into a python data structure - a list of dictonaries. In part two, we scraped the data from the mars temerpature data site and created a pandas dataframe with seven columns: id, terrestrial_date, sol, ls, month, min_temp, and pressure. The data types were converted into appropriate datetime, int, and float data types before beginning analysis. 

Results:
1. There are 12 months that exist on Mars.
2. There are 1867 Maritan day's worth of data.
3. The coldest month in Curiosity's location is month 3 with a average temperature of -83.307292.The hottest month in Curiosity's location is month 8 with a average temperature of -68.382979. Results were plotted on a bar chart.
4. The month with the lowest pressure is month 6 with an average pressure of 745.054422. The month with the highest pressure is month 9 with an average pressure of 913.30597. Results were plotted on a bar chart. 
5. Based on the graph, the distance from peak to peak is roughly 1424 - 750, indicating that a year on mars appears to be about 675 days. A quick internest serarch confirms that a Mars year is equivalent to 687 earth days.
6. The data was exported from the pandas dataframe into a CSV file.

Through the use of Stack Overflow, Github, and class notes, I was able to find the code for:
 - Creating an sorted index for scraped values: index = df.groupby("var").mean()[var2"].reset_index("var1").sort_values(var2")
 - Creating a bar plot with the sorted index: index.plot(x='var1',y='var2', kind = 'bar')





