[![Build Status](https://travis-ci.org/ukgovdatascience/eesectors.svg?branch=master)](https://travis-ci.org/ukgovdatascience/eesectors)
[![codecov.io](http://codecov.io/github/ukgovdatascience/eesectors/coverage.svg?branch=master)](http://codecov.io/github/ukgovdatascience/eesectors?branch=master)
[![GitHub tag](https://img.shields.io/github/tag/ukgovdatascience/eesectors.svg)]()

# eesectors

**This is a prototype and subject to constant development**

This package provides function used in the creation of a Reproducible Analytical Pipeline (RAP) for the Economic Estimates for DCMS sectors publication.

## Logging data issues to github

In order to use this functionality, it is necessary to set the three following environmental variables using `Sys.setenv()`:

|Name|Example|Description|
|---|---|---|
|GITHUB_PAT|_|A github personal access token with the necessary permissions.|
|LOG_REPO|RAP-demo-md|The name of a github repository where data issues can be logged.|
|LOG_OWNER|ukgovdatascience|The owner of the repository referred to in LOG_REPO.|


