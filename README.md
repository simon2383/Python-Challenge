# Python-Challenge
.................................................................Code Explanation for PyBank...........................................................

In Summary:
The PyBank script reads a CSV file containing financial data, calculates various financial metrics, and outputs the results to the terminal and a text file.

Explanation:
The PyBank script imports the os and csv modules and defines several variables to store financial data. The variables include months, which is an empty list to store the months in the dataset, profit_loss_changes, which is an empty list to store the changes in profit/losses between months, and several other variables to store financial metrics.

The script then changes the current working directory to the directory of the Python script and defines a path to the CSV file containing the financial data. The script then opens the CSV file using the csv module and reads the data row by row.

For each row of data, the script increments the count_months variable to keep track of the number of months in the dataset and adds the profit/loss value to the net_profit_loss variable to calculate the total profit/loss over the entire period. The script also calculates the change in profit/loss between the current month and the previous month and appends it to the profit_loss_changes list.

After reading all the data, the script calculates the average change in profit/loss over the entire period, as well as the greatest increase and decrease in profit/loss. The script then outputs the financial analysis to the terminal and a text file using the print and write functions.

.................................................................Code Explanation  for PyPoll.................................................................

In Summary:
The Python code reads in election data from a CSV file, calculates the total number of votes and the percentage of votes each candidate received, and outputs the results to the terminal and a text file.

Explanation
The Python code imports the necessary modules, including os, csv, and collections. It then defines two empty lists: voters_candidates and votes_per_candidate. The voters_candidates list is used to store the candidate each voter voted for, and the votes_per_candidate list is used to store the number of votes each candidate received.

The code then changes the current working directory to the directory of the Python script and sets the path to the election data CSV file. It then opens the CSV file and reads in the data using the csv.reader method. The header row is skipped, and the candidate each voter voted for is appended to the voters_candidates list.

The voters_candidates list is then sorted in ascending order, and the sorted list is arranged by the most common outcomes using the Counter method from the collections module. The number of votes each candidate received is appended to the votes_per_candidate list.

The code then calculates the percentage of votes each candidate received to three decimal points and prints the results to the terminal using the print function. It also exports the results to a text file using the open and writes methods.
