# Importing data into R

```
data <- read.delim(file.choose(), header = TRUE, sep = "\t", dec = ".")
```
After importing data, check the input.
```
dim(data)
head(data)
str(data)
```



[Back to Readme](https://github.com/tkostas/R-resources)