## Resubmission

This is a resubmission. In this version I have:

* Cut down the package size so that the package source tarball
`fivethirtyeight_0.4.0.tar.gz` is 4.9MB (less than 5MB CRAN limit). In the next
version of the package, we'll use the
[drat](https://journal.r-project.org/archive/2017/RJ-2017-026/index.html)
package to share larger datasets.

## Test environments

* ubuntu 14.04.5 (on travis-ci), R 3.4.2
* local OS X install, R 3.3.3
* win-builder (release)

## R CMD check results

There were no ERRORs, one NOTE on installed package size being 6.2Mb.
