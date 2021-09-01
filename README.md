README for `mooc-stats`


## Description

Statistical Analysis of MOOC Data.  We take data from a MOOC (Massive Online
Open Courses) platform and build statistics on participants of the course.
Notably statistics on the attendance of the course and the confidence of
participants in applying the knowledge in the material.

The main analysis builds a data model which can be fit onto new datasets.  The
`mooc-confidence-fl.ipynb` file contains the most throughout analysis and a
complete data model.  Construction of the notebook is divided into three parts:

1. Data Model
2. General Analysis
3. Extra Analysis

Given a new dataset one should be able to write a new part 1 (data model) and
the part 2 (general analysis) should just work on the new dataset - perhaps
with minimal tweaks.  An example of such new notebook is in
`edraak/edraak-mooc-confidence.ipynb`, which builds the same data model using
data collected from a different MOOC platform.


## Copying

Copyright (C) 2021 Michal Grochmal

This file is part of `mooc-stats`, which is distributed under the MIT license.

