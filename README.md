# Drone-based monitoring of antelope brush _(Purshia tridentata - Pursh)_

This project aims to create a protocol for using RGB drone imagery to monitor changes in antelope brush cover in the south Okanagan. It also evaluates how classification accuracy differs within- versus among- sites. 

## Description

The intended purpose of this project is to be used for automatically classifying drone-imagery of various antelope brush habitats across the south Okanagan in the hopes that it will provide a quicker and more efficient alternative to monitoring antelope brush sites. The classifier will output a classified raster, and the area and percent coverage of three land cover classes, antelope brush, ground and other vegetation. There are 7 classifiers, each tailored to a specific site. Imagery was collected in early May using a DJI Mavic 3E drone and flight routes were set up using Flighthub2. Each site was flown 38m above the ground at 3m/s and a course angle of 145 degrees with real-time terrain follow enabled. 

The error analysis portion evaluates how classification accuracy differs within- versus among-sites. It is completely separate from the classifiers and only aims to know how much the accuracy differs between the 7 different sites, and among subplots within each site. The scripts included are meant for obtaining the classification accuracies of subplots and running a random-effects ANOVA test. 

## Authors

Natalie Woo 

Email: natalie.woo@ubc.ca

