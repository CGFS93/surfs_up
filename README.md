# surfs up

## Overview of the Analysis:
Using Python, Pandas functions and methods, and SQLAlchemy, to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and for the month of December. then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. 

### Purpose:
Find information about temperature trends before opening the surf shop. Specifically, temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources

**Data Source:** "hawaii.sqlite" .

**Software:** Jupyter, Python.

## Results:

### Temp Summary Statistics for June:


-count:	1700.000000

-mean:	74.944118

-std:	3.257417

-min:	64.000000

-25%:	73.000000

-50%:	75.000000

-75%:	77.000000

-max:	85.000000



### Temp Summary Statistics for December:


-count:	1517.000000

-mean:	71.041529

-std:	3.745920

-min:	56.000000

-25%:	69.000000

-50%:	71.000000

-75%:	74.000000

-max:	83.000000


## Summary:
Result Development:
Write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June & December.
Convert the June & December temperatures to a list individually.
Create a DataFrame from the list of temperatures for the month of June & December.
Generate the summary statistics for June & December temperatures DataFrame.

Additional Queries:
Additional queries to further this analysis recommendations are to collect data of the average hours of sunshine per day, and
average wind speeds on the coast. These measurements would help determine quality of surfing and how many optimal hours of operation for the shop.
