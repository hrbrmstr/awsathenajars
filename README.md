
# awsathenajars

Java Archive Wrapper Supporting the ‘awsathena’ Package

## Description

Contains all supporting JARs for working with the AWS Java SDK for
Amazon Athena. Version number matches version number of included
‘aws-java-sdk-athena’ library.

## Installation

``` r
devtools::install_git("git@git.sr.ht:~hrbrmstr/awsathenajars")
# OR
devtools::install_gitlab("hrbrmstr/awsathenajars")
# OR
devtools::install_github("hrbrmstr/awsathenajars")
```

## Usage

``` r
library(rJava)
```

    ## 
    ## Attaching package: 'rJava'

    ## The following object is masked from 'package:bit':
    ## 
    ##     clone

``` r
library(awsathenajars)

packageVersion("awsathenajars")
```

    ## [1] '1.11.685'

## `awsathenajars` Metrics

| Lang  | \# Files | (%) | LoC |  (%) | Blank lines |  (%) | \# Lines |  (%) |
| :---- | -------: | --: | --: | ---: | ----------: | ---: | -------: | ---: |
| Java  |        2 | 0.2 |  28 | 0.34 |           5 | 0.21 |       18 | 0.27 |
| Maven |        1 | 0.1 |  22 | 0.27 |           3 | 0.12 |        0 | 0.00 |
| R     |        5 | 0.5 |  15 | 0.18 |           1 | 0.04 |       26 | 0.39 |
| make  |        1 | 0.1 |  10 | 0.12 |           4 | 0.17 |        0 | 0.00 |
| Rmd   |        1 | 0.1 |   7 | 0.09 |          11 | 0.46 |       22 | 0.33 |
