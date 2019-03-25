# Version - 0.1
# Author - Kanishka 

# Change and set the list of packages required and Run it Once.



set.seed(1234)
#Setting the required packages
pkgs <- c("shiny", "shinydashboard", "ggplot2", "ggthemes",                      # Add Packages R
          "party", "caret", "plotly", "curl", "RCurl", "e1071",
          "rpart", "ranger")

for(pkg in pkgs){
  if(!(pkg %in% rownames(installed.packages()))){
    install.packages(pkg, dependencies = TRUE)
  }
  lapply(pkg, FUN = function(X) {
    do.call("require", list(X))
  })
}
