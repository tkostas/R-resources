# Some basic data stuctures in R - vectors

Vector is the basic data structure in R.
It can be separated into 4 classes. <br>
- numeric <br>
- character <br>
- logical (TRUE or FALSE) <br>
- factor (for categorial variables) <br>

Use the assignment operator '<-', to create a vector and assign its value to a variable. By typing the variable name you print the values of the vector.
```
# for numeric vectors just assign the number
a <- 4

# for character vector type inside ""
a <- "4" 

# for logical
a <- TRUE

# for factor
a <- factor("A")

#type variable name to print the value 
```
Vectors can contain only one or multiple elements. However, all the elements mush be of the same class. 
```
# to concatenate multiple elements in one vector use the c() function 
## e.g. for numeric vector type:
a <- c(1, 3, 4, 5, 6) 

## for character
a <- c("A", "B", "C")
```




[Back to Readme](https://github.com/tkostas/R-resources)