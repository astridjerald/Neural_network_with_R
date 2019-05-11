# Neural Network using R

![Workshop Title](https://github.com/The-Assembly/Neural_network_with_R/blob/master/NeuralNetwork_with_R.jpg)

In this workshop, we’ll apply this to the field of machine learning and show you how you can use R to create and visualize a neural network that takes in a dataset and trains a model to predict outcomes.

![Digit Recognizer](https://github.com/The-Assembly/Neural_network_with_R/blob/master/DigitRecognizer.gif)

# What is R?
R is a programming language and free software environment for statistical computing and graphics.  The R language is widely used among statisticians and data miners for developing statistical software and data analysis.

# Advantages of using R
It’s open source language, related to other languages making it cross platform compatible.

# Installation Guide
Download R(*https://cran.r-project.org/bin/*) & RStudio (*https://www.rstudio.com/products/rstudio/download/*)

## Packages 
shiny - install.packages("shiny") <br/>
nnet - install.packages("nnet") <br/>
EBImage - install.packages("BiocManager") <br/>
          BiocManager::install("EBImage") <br/>

# Syntax in R
**ifelse()** function
x <- 5
if(x > 0){
  print("Non-negative number")
  } else {
       print("Negative number")
  }
**for** loop
for (year in 2010:2015){
  print(paste("The year is", year))
}

**while** loop
i <- 1
while (i < 6) {
  print(i)
  i = i+1
}

**break next** statement
x <- 1:5
for (val in x) {
  if (val == 3){
    break
  }
  print(val)
}

x <- 1:5
for (val in x) {
  if (val == 3){
    next
  }
  print(val)
}

**function**
new.function <- function(a) {
  for(i in 1:a) {
    b <- i^2
    print(b)
  }
}

new.function(6)

**Linear Regression and Curve Fitting**
