# Data_Wrangling

• We will mainly use dplyr
• Dplyr is a package contained in the tidyverse
• It contains useful functions for the manipulation/preparation of databases
• Reference material:

https://dplyr.tidyverse.org/
https://github.com/rstudio/cheatsheets/blob/master/data-transformation.pdf
Wickham, H. & Grolemund, G. R for Data Science: https://r4ds.had.co.nz/index.html
Data wrangling

• Pipe (%>%): chaining of several functions in sequence
• Rename: changing variable names
• Mutate: changing variable contents and creating new variables
• Filter: selecting observations based on logical criteria
• Select: selecting variables
• Summarise: creating tables with summary measures (descriptive statistics)
• Group by: grouping observations based on criteria
• Join: merging databases

The mentioned functions are some of the main tools provided by dplyr to make data wrangling in R easier. They allow to perform a wide range of operations on data frames, such as filtering rows, selecting specific columns, reordering data, adding new variables, summarizing data, and joining multiple datasets together. The pipe operator (%>%) is used to chain these operations in a sequence, making the code more readable.
