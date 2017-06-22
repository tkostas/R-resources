# Importing data into R
## Import from a delimited file
```
data <- read.delim(file.choose(), header = TRUE, sep = "\t", dec = ".")
```
After importing data, check the input.
```
dim(data)
head(data)
str(data)
```

## or import from excel file
```
#load readxl package (if not installed type first 'install.packages("readxl")')
library(readxl)

# check the tab names
excel_sheets(file.choose())   

# import tab of interest
data <- read_excel(file.choose(),     
           sheet = tab_name
           col_names = TRUE, 
           col_type = NULL, 
           skip = 0)    

```

[Back to Readme](https://github.com/tkostas/R-resources)