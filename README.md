# BatVision: Regression-Calibrated Single-View Computer Vision Pipeline for Precise Baseball Bat Analysis and Quality Control

## Introduction

Major League Baseball has long known that bat design shapes performance, yet geometry inside front offices is still captured with just a few caliper checks. Subtle variations that influence swing mechanics, contact quality, and durability go largely unmeasured, leaving teams to extrapolate from incomplete data. In partnership with the Baltimore Orioles, we developed BatVision, a computer vision pipeline that transforms bat geometry from manual snapshots into high-resolution, scalable profiles. By automating measurement, BatVision cuts processing time from minutes to seconds, expands detail by orders of magnitude, and reframes bat modeling from a bottleneck into a competitive advantage for quality assurance, individualized fitting, and opponent-equipment analysis.


## Data

For final benchmarking and validation, all ground-truth measurements and camera images were obtained from baseball bats used by active players on the Baltimore Orioles roster. This dataset includes high-resolution images and corresponding manual caliper measurements of seven game-used bats. Due to competitive concerns, and because neither the individual players nor the Baltimore Orioles management have granted permission to publicly release their bat geometry, this portion of the dataset remains private.

However, during the early development of our pipeline, we used non-proprietary bats for initial testing and prototyping. The dimensions and images of these bats are not subject to confidentiality restrictions and are included below. Please note that this subset, now publically released, does not comprise the full dataset used to train and evaluate the final version of the pipeline.


### Non-Proprietary Bat 1
**Ground-Truth Measurements**
| Measurement Interval (in) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 |
|----------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Measurements (mm)       | 62.4 | 62.6 | 63.1 | 63.1 | 63.0 | 62.5 | 61.8 | 60.6 | 59.3 | 56.9 | 54.4 | 51.1 | 48.0 | 44.9 | 42.1 | 39.2 | 36.7 | 34.5 | 32.7 | 31.1 | 29.7 | 28.5 | 27.6 | 26.8 | 26.1 | 25.4 | 24.9 | 24.4 | 24.0 | 23.8 | 25.1 | 30.0 | 38.1 |

**Image**
Please see /images/bat1.jpg

### Non-Proprietary Bat 2
**Ground-Truth Measurements**
| Measurement Interval (in) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 |
|----------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Measurements (mm)         | 64.3 | 64.5 | 64.5 | 64.5 | 64.3 | 64.0 | 63.2 | 62.2 | 61.0 | 59.2 | 56.6 | 53.6 | 50.3 | 47.2 | 43.9 | 40.4 | 37.1 | 34.5 | 32.3 | 30.2 | 29.0 | 27.4 | 26.2 | 25.4 | 24.1 | 23.6 | 23.1 | 22.9 | 23.1 | 24.1 | 26.9 | 32.8 | 43.7 |

**Image**
Please see /images/bat2.jpg



