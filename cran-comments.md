
## Resubmission
This is a re-submission. In response to a notification of GeSciLiVis v1.2.0 by Prof Brian Ripley I have changed:
- removed unstable dependency in aarch64-apple-darwin20 (64-bit) and x86_64-apple-darwin17.0 (64-bit) 

## Resubmission
This is a re-submission. In response to a notification of GeSciLiVis v1.1.0 by Prof Brian Ripley I have changed:
- removed unstable dependency

## Previous cran-comments
In response to review of GeSciLiVis v1.0.0 by Benjamin Altmann I have fixed:
- adding references in the description field of your DESCRIPTION file
- information messages not directly printed to the console 
(instead of print()/cat() rather use message()/warning() or
if(verbose)cat(..) (or maybe stop()))
- not changing the user's options par or working directory, and if so, doing so within functions, ensure with an *immediate* call of on.exit()

## Test environments
- local R installation, R 4.2.2
- win-builder (devel)
- R-hub Windows-x86_64-devel (r-devel)
- R-hub ubuntu-rchk (r-devel)
- R-hub ubuntu-gcc-release (r-release)

## R CMD check results

0 errors ✔ | 0 warnings ✔ | 1 note ✖

* This is a new release/new submission.