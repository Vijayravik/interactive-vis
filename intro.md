Interactive Visualisation
================

Understanding Interaction
-------------------------

> *“A picture is worth a thousand words. An interface is worth a thousand pictures.” - Ben Shneiderman*

-   Explore common interaction patterns:
    -   **Select**: mark something as interesting
    -   **Explore**: show me something else
    -   **Reconfigure**: show me a different arrangement
    -   **Encode**: show me a different representation
    -   **Abstract/Elaborate**: show me more or less detail
    -   **Filter**: show me something conditionally
    -   **Connect**: show me related items
-   Learn the principles of reactive programming
-   Allowing interactive data-model manipulation

``` r
url <- "http://visdown.com/data/cars.csv"
cars <- read.csv(url) 
str(cars)
```

    ## 'data.frame':    42 obs. of  6 variables:
    ##  $ brand: Factor w/ 13 levels "Chevrolet","Fiat",..: 1 1 1 1 2 2 2 3 3 4 ...
    ##  $ model: Factor w/ 42 levels "Alto","Alto 800",..: 4 28 29 31 20 19 25 8 15 3 ...
    ##  $ price: int  421 551 468 345 612 700 499 506 414 519 ...
    ##  $ kmpl : num  18.6 18.2 18.2 16.2 14.9 15.7 15.8 14.1 15.3 18 ...
    ##  $ bhp  : int  79 82 82 62 89 112 67 100 70 87 ...
    ##  $ type : Factor w/ 2 levels "Hatchback","Sedan": 1 2 1 1 2 2 1 2 1 2 ...
