Chicago Hockey Analytics
======

This repository will contain a set of analyses of player ability in the NHL.  It is designed to be a hub for experimentation, demonstration, and teaching about both data mining and hockey analysis.

<strong> Background </strong>

The models here are all  descendant from an academic <a href="http://arxiv.org/abs/1209.5026">paper</a> that uses relatively new techniques to estimate hockey player performance, written by <a href="http://faculty.chicagobooth.edu/robert.gramacy">Bobby Gramacy</a>, <a href="http://www-stat.wharton.upenn.edu/~stjensen">Shane Jensen</a>, and <a href="http://faculty.chicagobooth.edu/matt.tadd">Matt Taddy</a> applies regularized logistic regression to predict the probability that either team on the ice scored any given goal.  The contribution of individual players to this for-vs-against goal probability is then taken as a measurement of their on-ice contribution.  It is a sort of regression-adjusted Plus-Minus.

<strong> Content </strong>

The repository contains R code to first pull the relevant data from nhl.com (using the nhlscrapr tool from <a href="http://www.acthomas.ca/comment/">A.C. Thomas</a>), and then do a series of analyses using sparse regularized regression.
The documentation will consist of lecture slides and be accompanied by a hockey blog by Gramacy and Taddy.

<strong> Teaching </strong>

This general 'hockey problem' combines an intuitive estimation question (who influences the outcome?) with difficult high-dimensional data (e.g., who was on-ice?).  It turns out that the general example is a fantastic tool for teaching data mining methods.  Indeed, at the end of quarter I (MT) realized that I'd mentioned the `hockey data' in almost every lecture of the <a href="http://faculty.chicagobooth.edu/matt.taddy/teaching">data mining class</a> that I teach at Chicago Booth.  Thus as appropriate this repository will also contain code to illustrate core data mining techniques, including principal components regression, K-means clustering, random forests, and much else.   
