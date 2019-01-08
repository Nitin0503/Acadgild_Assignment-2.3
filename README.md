# Acadgild_Assignment-2.3
1. How to Import SAS XPORT Files into R With The foreign package
Answer: library(foreign)
read.xport(foreign)
read.xport(file)

2. How To Import SAS Files into R With The haven Package?
Answer: install.packages("haven")
x<-read_sas("path to file","path to formats catalog")
read_sas(path)
3. How to read Weka Attribute-Relation File Format (ARFF) files in R?
Answer: library(foreign)
read.arff(file)

4. How to read a heavy csv/tsv file using readr package?
Answer: read.csv("file path.csv")
