About lapsolver
===============

Home: https://github.com/cheind/py-lapsolver

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Fast linear assignment problem (LAP) solvers for Python based on c-extensions

py-lapsolver implements a linear sum assignment problem solver for dense matrices based
on shortest path augmentation. In practice, it solves 5000x5000 problems in around 3 seconds.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/lapsolver-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/lapsolver-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lapsolver-green.svg)](https://anaconda.org/loopbio/lapsolver) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/lapsolver.svg)](https://anaconda.org/loopbio/lapsolver) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/lapsolver.svg)](https://anaconda.org/loopbio/lapsolver) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/lapsolver.svg)](https://anaconda.org/loopbio/lapsolver) |

Installing lapsolver
====================

Installing `lapsolver` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `lapsolver` can be installed with:

```
conda install lapsolver
```

It is possible to list all of the versions of `lapsolver` available on your platform with:

```
conda search lapsolver --channel loopbio
```




Updating lapsolver-feedstock
============================

If you would like to improve the lapsolver recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/lapsolver-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.