# joineR 1.2.5.9000

## Housekeeping

* Relaxed dependency on R (>= 3.6) introduced in the previous version.

# joineR 1.2.4

## Housekeeping

* Added Zenodo badge to README.

* Added further ORCID IDs for authors.

* Changed package maintainer to Pete Philipson.

# joineR 1.2.3

## Bugs

* Fixed errors when subjects IDs were `character` format.

## Housekeeping

* Added ORCID IDs for authors.

* Added Depsy badge to README.

# joineR 1.2.2

## Minor update

* Modified the control parameters for the call to `nlme::lme()` that is used to
generate initial parameter estimates. In some bootstrap settings, this was
throwing an error, leading to the entire bootstrap run to cease.

## Housekeeping

* Added hex sticker badge.

# joineR 1.2.1

## Minor updates

* Added Rd file for `joint.object` to describe what is contained in an object of
class `joint`.

* Added the ubiquitous `aids` dataset for teaching purposes.

## Bugs

Fixed an error in the `liver` dataset.

## Maintanence

* Updated the documentation for the datasets.

* Added `ByteCompile: true` to the DESCRIPTION.

# joineR 1.2.0

## Major updates

* `joint` now allows for competing risks data (2 failure types) as per the model
developed by Williamson et al. (2008). Other functions have been upgraded to
handle the competing risks data.

* A second vignette for the competing risks model is available.

## Minor updates

* R version 3.4.0 deprecated the recycling of 1x1 matrices, and led to warnings
being thrown. This is now fixed.

## Maintanence

* General code and documentation tidy-up.

* New unit tests added to increase code coverage.

# joineR 1.1.0

## Minor updates

* Add `simjoint` function to simulate data from joint models with several types
of association structures.

* Removed `jlike` function and integrated likelihood calculation directly into
`em.alg` function.

* Minor bug fixes to the `joint` and `em.alg` functions.

## Maintanence

* Added a `NEWS.md` file to track changes to the package.

* Added some unit tests + code coverage monitoring integration.

* Converted Rd files to roxygen.

* Converted Sweave vignette to rmarkdown.

* Updates to vignette and documentation.

* Minor updates to `DESCRIPTION` and `NAMESPACE` to pass R CMD checks, provide
additional information, and removed dependency of `boot` and `gdata` packages.

* Added a `README.Rmd`.

* Added project to GitHub with integrated Travis CI and appveyor.

# joineR <1.1

* First version of software with subsequent minor patches. No NEWS file was
maintained prior to version 1.1



