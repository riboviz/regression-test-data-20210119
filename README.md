# RiboViz regression test data 19/01/2021

Provenance:

* URL: https://github.com/riboviz/riboviz
* Date: 19/01/2021
* Branch: develop
* Commit: 7aad0d0385ef62bb0e0f86f4849e4e15929f0d3e
* Environment: see [environment.txt](./environment.txt)

Usage:

```console
$ git clone https://github.com/riboviz/regression-test-data-20210119
$ cd riboviz
$ pytest riboviz/test/regression/test_regression.py --expected=$HOME/regression-test-data-20210119 --nextflow
```

For full instructions see the RiboViz developer guide in the RiboViz repository.
