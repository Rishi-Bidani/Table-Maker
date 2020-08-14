# Table-Maker

This is a simple table maker for python


This uses colors for the heading so,
You should have **colorama** on your device to use this.

## Initialise the table as follows:

```table1 = TableMaker(3, [20, 15, 10], "cyan") ```
###### => number_of_columns, [maximum_lenghts_for_column], colour
###### colours available are => BLACK, RED, GREEN, YELLOW, BLUE, MAGENTA, CYAN, WHITE
```
heading1 = ["title1", "title2", "title3"]
row1 = ["item1", "item2", "item3"]
row2 = ["another1", "another2", "another3"]

table1.heading(heading1)
table1.items(row1)
table1.items(row2)
table.bottomline()
```
This will create a simple table
