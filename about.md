---
layout: page
title: About
permalink: /about/
---

Grad Student at NCSU.  Career technology sales exec.

### Interest in Stats and Data Science

Very interested to see how AI / ML will impact the IT services industry.

### Contact me

[tkidol@ncsu.edu](mailto:tkidol@ncsu.edu)

### Code Fun
Here's some sample code for an RMD file to plot iris data set sample lengths by widths for ea species to get started

```{r, codefun, echo=TRUE}
ibrary(ggplot2)
ggplot(iris, aes(x = Sepal.Length, y = Sepal.Width)) + 
  geom_point() + 
  facet_wrap(~ Species, ncol = 2, scales="free")
```

