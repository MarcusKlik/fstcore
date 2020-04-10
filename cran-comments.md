
## Submission

## Test environments 

* OSX on travis-ci (version 10.13.6)
* Ubuntu Ubuntu 16.04.6 LTS on travis-ci
* Ubuntu 19.10 locally
* Ubuntu 19.10 locally using clang-6.0
* Docker with the rocker/r-devel-ubsan-clang instrumented image
* Local Ubuntu with instrumenten image using clang-10
* Windows 10 local R 3.6.4
* Windows 10 local R-dev 4.0.0 pre-release (r77640)
* Windows Server 2012 R2 x64 (build 9600) on AppVeyor (R 3.6.3)
* Singularity-container package for running rchk on Ubuntu 18.10
* Valgrind on Ubuntu 19.10.
* Rhub (all available systems)

## R CMD check results

There are no errors or warnings.

## Downstream dependencies

I have run R CMD check on downstream dependencies and found no issues.