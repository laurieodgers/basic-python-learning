# Exercise 1

This is an exercise around CSV.

A green grocer requires that CSV files be converted into something that can be
of use to a human.

This involves printing the data in a human friendly format & adding appropriate
symbols ($), and performing certain calculations to make things easier to read.

1. Read data.csv into a python variable
1. Interpret it line-by-line using either split(), or a CSV library of
your choice
1. Iterate over each line in the file, printing its comments separated by a
single space
1. Print the subtotal per line (amount_purchased * cost_per_unit) in CLI as the
far right hand column. You may need to cast these values as int()

## Challenge:

Format the output as a receipt.

1. Include a string variable "companyName" and set it to "ACME Produce Pty Ltd"
1. Print the company name at the top of the receipt.
1. Format the CSV in a table so that everything lines up correctly (strings = left align, numbers = right align)
1. Print a total at the end of the script. Note you may need to use int() to cast the  read in from the CSV
