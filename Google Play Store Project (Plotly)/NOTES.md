## Pandas
### pandas.value_counts()
Returns total number of values in a specified column

	- `df.ColumnName.value_counts()`
	- Returns	value1(category1) > Number of appearances
			value2(category2) > Number of appearances
## Plotly
### plotly.express.pie.update_traces()
If you’d like to configure other aspects of the chart, that you can’t see in the list of parameters, you can call a method called `.update_traces()`. In plotly lingo, “traces” refer to graphical marks on a figure. Think of “traces” as collections of attributes.

	- fig = px.pie(label, values)
	- fig.update_traces(textposition='outside', textinfo='percent+label')
