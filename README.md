# Aging_Work_Orders
A report to see how long the open work orders remain in the tech's queue

One of the problems we found was that some techs were leaving work orders in their queue without completing them. This report is run monthly to give the managers a sense of the work orders that are in the tech's queue and how long they have been there.

The program uses a SQL query to get the list of open work orders from the database, and then they are sorted into a new dataframe where each is categorized by how old it is.
