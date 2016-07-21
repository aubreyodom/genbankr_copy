## Package

The `genbankr` package is part of the Bioconductor ecosystem of R packages. As
such, it's primary splash page - including continuous integration and testing
badges - can be found [here](https://bioconductor.org/packages/release/bioc/html/genbankr.html).


## Introduction

`genbankr` is a package which provides utilities to parse GenBank and GenPept 
files into data structures which integrate with the Bioconductor ecosystem.

## Installation

This package depends on the [Bioconductor](http://bioconductor.org) ecosystem of
R packages. If you already have a version of Bioconductor (>=3.3) installed,
you can do gthe following:

```
libary(BiocInstaller)
biocLite("genbankr")
```

If you do not currently have the Bioconductor core machinery installed, you can
get the current or release version like so:

```
source("http://bioconductor.org/biocLite.R")
``` 
for release and

```
source("http://bioconductor.org/biocLite.R")
try(useDevel(TRUE))
```
For devel.

After doing one of the above (once), you can install `genbankr` as above, via

```
library(BiocInstaller)
biocLite("genbankr")
```

Note that Bioconductor is a sychronized development and release
platform, so release and development versions of Bioconductor packages
cannot be safely mixed in the same package (installation) library. Use `switchr`
or direct `.libPaths` management to maintain multiple side-by-side installations
if necessary.

To install directly from github (this will generally not be necessary
unless you intend to contribute to `genbankr`'s development), do

```
source("http://bioconductor.org/biocLite.R")
try(useDevel(TRUE))
biocLite("gmbecker/genbankr")
```

The Bioconductor development repository will contain
the latest development version of genbankr which has passed testing (lagged
by about a day).

## Code of Conduct

This project operates under the Contributor Covenenant Code of Coduct [see here](./CONDUCT.md)