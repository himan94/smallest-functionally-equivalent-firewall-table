# smallest-functionally-equivalent-firewall-table
Designing a GUI powered application in python that can create the smallest functionally equivalent firewall table 
To produce the smallest functionally equivalent firewall table you need to implement the following
functions:

1. Merge redundant rules (same servers, same ports) if any.
2. Identify ports that are referenced frequently in all the rules, and consolidate them in their
own rules, and assign the servers to that rules.
3. Try to join the server with the smallest number of rules.
4. Try to make the rule have the smallest number of ports without increasing the table size.
5. For goals 3 and 4 above, if they conflict, pick the one that would reduce the number of rows
in the output table as much as possible.


THe final command line statement would look something like this : myapp -i input.csv -o output.csv

This is replaced by a GUI that looks like the figure in the file GUI output thus making the whole application more user friendly

