Using Python to automate the cleansing and transformation of a software output.
This is an example of a software output that I use every day, so creating a script that automatically cleans and transforms the output saves me a lot of time every day.

The software is a logistics platform that gives us the price to ship something from one city to another city. In logistics, there are different factors that determine price, like the type of truck (refrigerated truck or dry truck)
The output gives us the price of a refrigerated truck for each shipment, but we want to also add the total price for dry trucks and the price/LB for each truck type as well.

The script that I wrote:
- Cleans the data (removes unnecessary rows and columns, renames columns and sets titles)
- Adds columns that gives us pricing details for different truck types
- Uses indexing method (for loop) to find positions of columns for easier data cleaning
- Changes data types to correct data type for analysis
- Conducts exploratory analysis to check for nulls and anything else that would stand out
- Exports final dataset to Excel
