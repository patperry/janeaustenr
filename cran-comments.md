## Release summary

This is the sixth CRAN release of janeaustenr; it fixes an encoding issue for some of the text.

## Test environments

* Local OS X install: R 3.4.0
* Ubuntu 12.04 (on Travis-CI): R 3.4.0
* Win-builder: R-devel and R-release

## R CMD check results

0 errors | 0 warnings | 0 notes

There was a message about possibly mis-spelled words in DESCRIPTION ("Austen's" at 2:13 and 5:34, "Northanger" at 7:32).

* Those words are spelled correctly.


## Downstream dependencies

I ran R CMD check on the downstream dependencies (results at https://github.com/juliasilge/janeaustenr/tree/master/revdep) and there were no problems related to janeaustenr.