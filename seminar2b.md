Seminar 2b
================
Theodore Smith
January 10, 2018

Deliverable
-----------

``` r
library(ggplot2)
ggplot(data=mpg) + geom_point(mapping=aes(x=displ,y=hwy,color=drv,size=class))
```

    ## Warning: Using size for a discrete variable is not advised.

![](seminar2b_files/figure-markdown_github/deliverablePlot-1.png)
