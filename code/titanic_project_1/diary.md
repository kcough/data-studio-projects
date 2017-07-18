notes for first project on Titanic survivors

First, in thinking about the project, we need a level of analysis I don't have yet--the survival rate (maybe in percentage) of passengers.

This could be calculated by taking all of the people who paid $100 for a ticket and finding the percentage of them that survived. This is the likelihood of survival rate for that fare.

Let's think about this.

For instance: 1294 people paid 16.1000 GBP for a ticket. Filter the dataset to have only those people in it. Then run a value_counts() on the survived column. Let's say 560 people survived out of those who paid 16 GBP. Divide 560 by 1294. That's a 43% survival rate for that fare price.

If we do this for each fare price we should get a survival rate. Let's try it once and see if we can get where we need to go.

We need to then make a new column: estimated survival rate. This would be the percentage. So for instance, if the person paid 26.0000 pounds, they would have a 38% expected survival rate, based on the analysis. The column would be on the end and so for each fare there would be a survival rate associated with that fare.

Here's what we want as a new dataframe:

fare / # survivors # / # who purchased the fare / # survival % rate


TO DO THIS FOR THE WHOLE DATAFRAME:

Maybe we could groupby fare to get a dataframe organized by fare price and the number of passengers paying that price.

USEFUL SITES:

Here's some interesting info on fare prices and how they were calculated for this dataset:
http://www.statisticalconsultants.co.nz/blog/titanic-fare-data.html

Analysis done by someone else: http://www.anesi.com/titanic.htm
