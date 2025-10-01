# BatVision: Regression-Calibrated Single-View Computer Vision Pipeline for Precise Baseball Bat Analysis and Quality Control

## Introduction

Major League Baseball has long known that bat design shapes performance, yet geometry inside front offices is still captured with just a few caliper checks. Subtle variations that influence swing mechanics, contact quality, and durability go largely unmeasured, leaving teams to extrapolate from incomplete data. In partnership with the Baltimore Orioles, we developed BatVision, a computer vision pipeline that transforms bat geometry from manual snapshots into high-resolution, scalable profiles. By automating measurement, BatVision cuts processing time from minutes to seconds, expands detail by orders of magnitude, and reframes bat modeling from a bottleneck into a competitive advantage for quality assurance, individualized fitting, and opponent-equipment analysis.


## Data

For final benchmarking and validation, all ground-truth measurements and camera images were obtained from professional baseball bats used by MLB players and provided by the Baltimore Orioles. Each bat was marked at one-inch intervals along its length with pencil, and diameters at each mark were measured with calipers three to four times per interval, with the average recorded to minimize noise and measurement error. This produced a dense, high-resolution, and reproducible geometric profile that served as ground truth for evaluating the pipeline.

During the early development and internal testing phase, before the Orioles dataset was incorporated, we trialed this measurement procedure on non-proprietary bats. As an illustrative example, we collected measurements on a Louisville Slugger WBL2689 (Genuine MIX Natural, 34-inch) bat. This all-natural wood model features an uncupped barrel design, an unfinished handle for grip, and the iconic Louisville Slugger branding. The product page is available at: [slugger.com](https://www.slugger.com/en-us/product/genuine-mix-natural-wbl2689?ef_id=CjwKCAjw_-3GBhAYEiwAjh9fUK_feS41eyZIyxvYTorBjdtwlIWU0bEgSLPkNzm0cHCjlAeYFFj9GxoC0KAQAvD_BwE:G:s&s_kwcid=AL!15981!3&utm_source=x&utm_medium=ps|shp|dy&utm_campaign=SEM_PMAX_SLUGGER_BTG_BASEBALL&cmpid=ps|shp|dy|x|SEM_PMAX_SLUGGER_BTG_BASEBALL|&gad_source=1&gad_campaignid=17190794525&gbraid=0AAAAADcc_XA4C2CmFkEYkt81jyUxw-b4f&gclid=CjwKCAjw_-3GBhAYEiwAjh9fUK_feS41eyZIyxvYTorBjdtwlIWU0bEgSLPkNzm0cHCjlAeYFFj9GxoC0KAQAvD_BwE
).
For this bat, as with the Orioles dataset, each one-inch mark was measured multiple times with calipers and averaged to ensure consistency. The images and averaged caliper data for this development bat are publicly released to demonstrate the methodology.

While the WBL2689 example highlights the protocol in a transparent and replicable way, the Orioles-provided professional bats remain the core dataset for this project, all measured with the identical pencil-marking and repeated-caliper procedure to ensure comparability and rigor.

### Non-Proprietary Bat 1
**Ground-Truth Measurements:**
| Measurement Interval (in) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 |
|----------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Measurements (mm)       | 62.4 | 62.6 | 63.1 | 63.1 | 63.0 | 62.5 | 61.8 | 60.6 | 59.3 | 56.9 | 54.4 | 51.1 | 48.0 | 44.9 | 42.1 | 39.2 | 36.7 | 34.5 | 32.7 | 31.1 | 29.7 | 28.5 | 27.6 | 26.8 | 26.1 | 25.4 | 24.9 | 24.4 | 24.0 | 23.8 | 25.1 | 30.0 | 38.1 |

**Image:**
Please see /images/bat1.jpg

### Non-Proprietary Bat 2
**Ground-Truth Measurements:**
| Measurement Interval (in) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 | 33 |
|----------|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Measurements (mm)         | 64.3 | 64.5 | 64.5 | 64.5 | 64.3 | 64.0 | 63.2 | 62.2 | 61.0 | 59.2 | 56.6 | 53.6 | 50.3 | 47.2 | 43.9 | 40.4 | 37.1 | 34.5 | 32.3 | 30.2 | 29.0 | 27.4 | 26.2 | 25.4 | 24.1 | 23.6 | 23.1 | 22.9 | 23.1 | 24.1 | 26.9 | 32.8 | 43.7 |

**Image:**
Please see /images/bat2.jpg



