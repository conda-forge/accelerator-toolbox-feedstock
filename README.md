About accelerator-toolbox-feedstock
===================================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/accelerator-toolbox-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/atcollab/at

Package license: Apache-2.0

Summary: Toolbox for modeling particle accelerators

Documentation: https://atcollab.github.io/at/

Accelerator Toolbox (AT) is a collection of tools to model storage rings and beam transport lines.
With AT, it is possible to:
- **create and manipulate accelerator lattice elements**,
- **track particles through the lattice**, selecting the appropriate integrator to represent the physics
- **compute accelerator parameters and beam properties**, generating new scripts or taking advantage of the existing ones


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_numpy1.22python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_numpy1.22python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.22python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_numpy1.22python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.22python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_numpy1.22python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.23python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_numpy1.23python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_numpy1.26python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_numpy1.26python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.22python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_numpy1.22python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.22python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_numpy1.22python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.22python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_numpy1.22python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.23python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_numpy1.23python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_numpy1.26python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_numpy1.26python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.22python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=win&configuration=win%20win_64_numpy1.22python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.22python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=win&configuration=win%20win_64_numpy1.22python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.22python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=win&configuration=win%20win_64_numpy1.22python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.23python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=win&configuration=win%20win_64_numpy1.23python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_numpy1.26python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22858&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/accelerator-toolbox-feedstock?branchName=main&jobName=win&configuration=win%20win_64_numpy1.26python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-accelerator--toolbox-green.svg)](https://anaconda.org/conda-forge/accelerator-toolbox) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/accelerator-toolbox.svg)](https://anaconda.org/conda-forge/accelerator-toolbox) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/accelerator-toolbox.svg)](https://anaconda.org/conda-forge/accelerator-toolbox) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/accelerator-toolbox.svg)](https://anaconda.org/conda-forge/accelerator-toolbox) |

Installing accelerator-toolbox
==============================

Installing `accelerator-toolbox` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `accelerator-toolbox` can be installed with `conda`:

```
conda install accelerator-toolbox
```

or with `mamba`:

```
mamba install accelerator-toolbox
```

It is possible to list all of the versions of `accelerator-toolbox` available on your platform with `conda`:

```
conda search accelerator-toolbox --channel conda-forge
```

or with `mamba`:

```
mamba search accelerator-toolbox --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search accelerator-toolbox --channel conda-forge

# List packages depending on `accelerator-toolbox`:
mamba repoquery whoneeds accelerator-toolbox --channel conda-forge

# List dependencies of `accelerator-toolbox`:
mamba repoquery depends accelerator-toolbox --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating accelerator-toolbox-feedstock
======================================

If you would like to improve the accelerator-toolbox recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/accelerator-toolbox-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@lfarv](https://github.com/lfarv/)

