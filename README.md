npExact
=======
[![Travis-CI Build Status](https://travis-ci.org/zauster/npExact.png?branch=master)](https://travis-ci.org/zauster/npExact)
[![codecov](https://codecov.io/gh/zauster/npExact/branch/master/graph/badge.svg)](https://codecov.io/gh/zauster/npExact)
[![Rdoc](http://www.rdocumentation.org/badges/version/npExact)](http://www.rdocumentation.org/packages/npExact) 


Installation
------------

As this package is still in development, but can already be
installed through CRAN.

```r
install.packages("npExact")
```

The development version can be installed using the `devtools`
package:

```r
if (!require('devtools')) install.packages('devtools')
install_github("zauster/npExact")
```


Usage
-----

After installation, load the package with:

```r
library(npExact)
```

See the help-files for some examples of the usage of the package.

```r
help("npExact")
```

Contributing
-----

First of all, I am happy if you use the package and even happier
if you want to contribute.

Open an issue if you think you found a bug or if you have an idea
for a new feature.

Contributions are best done through pull requests (have a look at
the current development at the [develop
branch](https://github.com/zauster/npExact/tree/develop)). Please
run `R CMD build npExact` and `R CMD check
npExact_VERSION.tar.gz` before you submit your changes.
