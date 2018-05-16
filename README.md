About trilinos
==============

Home: https://trilinos.org/

Package license: Sandia LGPL-compatible and BSD-compatible SNAFU

Feedstock license: BSD 3-Clause

Summary: Framework for multi-physics engineering and scientific problems

The Trilinos Project is an effort to develop algorithms and enabling
technologies within an object-oriented software framework for the
solution of large-scale, complex multi-physics engineering and
scientific problems. A unique design feature of Trilinos is its focus
on packages.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/trilinos-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/trilinos-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/trilinos-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/trilinos-feedstock)
Windows: ![](https://cdn.rawgit.com/conda-forge/conda-smithy/90845bba35bec53edac7a16638aa4d77217a3713/conda_smithy/static/disabled.svg)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/guyer/trilinos/badges/version.svg)](https://anaconda.org/guyer/trilinos)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/guyer/trilinos/badges/downloads.svg)](https://anaconda.org/guyer/trilinos)

Installing trilinos
===================

Installing `trilinos` from the `guyer` channel can be achieved by adding `guyer` to your channels with:

```
conda config --add channels guyer
```

Once the `guyer` channel has been enabled, `trilinos` can be installed with:

```
conda install trilinos
```

It is possible to list all of the versions of `trilinos` available on your platform with:

```
conda search trilinos --channel guyer
```




Updating trilinos-feedstock
===========================

If you would like to improve the trilinos recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`guyer` channel, whereupon the built conda packages will be available for
everybody to install and use from the `guyer` channel.
Note that all branches in the conda-forge/trilinos-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.