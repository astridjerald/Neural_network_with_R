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

# Syntax in R <br/>
**ifelse()** function <br/>
x <- 5 <br/>
if(x > 0){ <br/>
  print("Non-negative number") <br/>
  } else { <br/>
       print("Negative number") <br/>
  } <br/>
**for** loop <br/>
for (year in 2010:2015){ <br/>
  print(paste("The year is", year)) <br/>
} <br/>

**while** loop <br/>
i <- 1 <br/>
while (i < 6) { <br/>
  print(i) <br/>
  i = i+1 <br/>
} <br/>

**break next** statement <br/>
x <- 1:5 <br/>
for (val in x) { <br/>
  if (val == 3){ <br/>
    break <br/>
  } <br/>
  print(val) <br/>
}

x <- 1:5 <br/>
for (val in x) { <br/>
  if (val == 3){ <br/>
    next <br/>
  } <br/>
  print(val) <br/>
} <br/>

**function** <br/>
new.function <- function(a) { <br/>
  for(i in 1:a) { <br/>
    b <- i^2 <br/>
    print(b) <br/>
  } <br/>
} <br/>

new.function(6) <br/>

**Linear Regression and Curve Fitting** <br/>
Run the code from curvefit.R <br/>
![](https://github.com/The-Assembly/Neural_network_with_R/blob/master/curvefit.R)
