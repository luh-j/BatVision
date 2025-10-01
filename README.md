# BatVision: Regression-Calibrated Single-View Computer Vision Pipeline for Precise Baseball Bat Analysis and Quality Control

## Introduction

From early swing analytics to today’s torpedo bats, Major League Baseball has long recognized that bat design matters. Yet, despite bats being the only point of contact on offense between a team’s $325 million payroll and baseball, bat geometry remains under-measured — typically reduced to a few manual caliper checks.   

Subtle geometric variations affect swing mechanics and contact quality, yet without high-resolution, scalable tools, their impact remains hard to quantify. Lacking sharper data and faster workflows, teams are forced to extrapolate from incomplete information. Bat geometry isn’t an overlooked variable — it’s a well-known gold mine constrained by manual methods.  

In partnership with Sig Mejdal and John Asel of the Baltimore Orioles, we introduce BatVision, an automated pipeline that transforms bat geometry from manual checks into a scalable competitive edge. Providing reproducible, high-resolution measurements at scale, BatVision cuts inventory processing time, informs GMs how design choices affect on-field performance, and enables downstream applications such as individualized bat fitting, manufacturing QA, and opponent-equipment analysis.  


## Data

For final benchmarking and validation, all ground-truth measurements and camera images were obtained from baseball bats used by active players on the Baltimore Orioles roster. This dataset includes high-resolution images and corresponding manual caliper measurements of seven game-used bats. Due to competitive concerns, and because neither the individual players nor the Baltimore Orioles management have granted permission to publicly release their bat geometry, this portion of the dataset remains private.

However, during the early development of our pipeline, we used non-proprietary bats for initial testing and prototyping. The dimensions and images of these bats are not subject to confidentiality restrictions and are included below. Please note that this subset, now publically released, does not comprise the full dataset used to train and evaluate the final version of the pipeline.

### Non-Proprietary Bat 1
| Measurement Interval (in) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 |
|----------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Measurements (mm)       | 62.4 | 62.6 | 63.1 | 63.1 | 63.0 | 62.5 | 61.8 | 60.6 | 59.3 | 56.9 | 54.4 | 51.1 | 48.0 | 44.9 | 42.1 | 39.2 | 36.7 | 34.5 | 32.7 | 31.1 | 29.7 | 28.5 | 27.6 | 26.8 | 26.1 | 25.4 | 24.9 | 24.4 | 24.0 | 23.8 | 25.1 | 30.0 | 38.1 |






