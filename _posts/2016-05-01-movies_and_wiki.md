---
layout: post
title: Using Wiki Data to Predict Box Office Revenue
date: 2016-05-01
---

Wiki traffic data seems to be a good proxy for audience interest in a movie relatively close to a movie's release.  But does this trend hold as we increase the timespan?

As seen in figure 1, there seems to be a loose relationship at best between wiki views and future box office revenue, when looking at wiki page views at least one year in advance of the release date.

![Figure 1 - Scatter Plot of Wiki Views vs. Box Office Revenue](/images/Image1.png =250x100)

Compare this to figure 2, where the relationship between between a movie's production budget and it's future box office revenue is much clearer.

![Figure 2 - Scatter Plot of Production Budget vs. Box Office Revenue](/images/Screen Shot 2016-04-29 at 10.34.17 AM.png)

Table 1 has a sparse model with wiki views as the only predictor and future box office revenue as the outcome.  

![Table 1 - Sparse model with wiki views only](/images/Screen Shot 2016-05-02 at 9.14.29 AM.png)


Table 2 includes production budget and genre - specifically, note how adding these additional predictors causes wiki views to completely lose what little predictive power it had.

![Table 2 - Complete model with wiki views, production budget, and genre](/images/Screen Shot 2016-05-02 at 9.14.39 AM.png)


