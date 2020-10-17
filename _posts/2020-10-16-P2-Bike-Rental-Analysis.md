---
layout: post
title: "Bike Rental Analysis"
---
You can get to the project repo and access the daily analyses through the GH pages site [here](https://tkidol.github.io/ST558-Project-2/).

This project proved the value of R & the related packages in a big way.  As before, dplyr simplified manipulation of the data while the caret package did the same for train/test data creation & regression/boosted tree predictions. Most of all, the project exercised my (developing) statistics and (also developing) coding skills in a meaningful way.  I could easily see a firm hiring a data scientist to execute this kind of analysis to improve their business operations, control costs and prepare for seasonal demand.     

My comfort level with RStudio has grown and it made the data management and summary analysis easier than the NHL project.  That was very helpful as I spent a considerable amount of time workig to understand the data to prepare for the predictive modeling.  This enabled me to choose relevant predictors quickly and devote time to tuning the models for best mix of outcomes (lower rmse) at a reasonable computational cost (time).  

Despite that advantage, the biggest challenge was the time it takes for the modeling to execute.  The importance of getting the most out of each modeling run to minimize wait time to facilitate more complex analyses on even larger data sets in the future.  Also, since final model and tuning decisions were derived for "Monday" the final model selections did not always hold for the other 6 days (e.g. a CP value for R-Tree on Monday may not produce the lowest RMSE for Sunday).  Automating final model selection by choosing the best tuning values from the candidate models' "$results" table would overcome this limitation.

