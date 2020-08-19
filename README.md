About hunter
============

Home: https://github.com/ionelmc/python-hunter

Package license: BSD-2-Clause

Feedstock license: BSD-3-Clause

Summary: Hunter is a flexible code tracing toolkit



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.8" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.8" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=win&configuration=win_64_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=win&configuration=win_64_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.8</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=126&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/hunter-feedstock?branchName=master&jobName=win&configuration=win_64_python3.8" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-hunter-green.svg)](https://anaconda.org/nsls2forge/hunter) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/hunter.svg)](https://anaconda.org/nsls2forge/hunter) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/hunter.svg)](https://anaconda.org/nsls2forge/hunter) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/hunter.svg)](https://anaconda.org/nsls2forge/hunter) |

Installing hunter
=================

Installing `hunter` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `hunter` can be installed with:

```
conda install hunter
```

It is possible to list all of the versions of `hunter` available on your platform with:

```
conda search hunter --channel nsls2forge
```




Updating hunter-feedstock
=========================

If you would like to improve the hunter recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/hunter-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


