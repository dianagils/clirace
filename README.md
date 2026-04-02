# clirace

**clirace** is an extension of the iRACE framework that enhances configuration space exploration through intelligent clustering of elite configurations.

## Overview

clirace introduces a clustering-based approach to improve irace's exploration behavior. The strategy groups elite configurations based on their location in the parameter space and selects parent configurations from these groups to guide the sampling of new configurations. This extends irace's exploratory capabilities by better leveraging the diversity of high-performing configurations.

## Branches

clirace supports two different clustering algorithms:

### grid-clustering (default)
Grid-based clustering that partitions the parameter space into a grid structure. The number of partitions can be configured to control the granularity of the clustering.

### k-medoids
K-medoids clustering algorithm implementation for grouping elite configurations based on their distance in the parameter space.

## Setup Instructions

[**User Guide (PDF)**](https://cran.r-project.org/package=irace/vignettes/irace-package.pdf) 

## Attribution

Based on **irace** - Copyright (C) 2010-2020 Manuel López-Ibáñez, Jérémie Dubois-Lacoste and Leslie Pérez-Cáceres.
