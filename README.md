# da-plots

This repository contains a notebook that generates an **experimental** differential abundance barplot from ANCOM-BC data generated with QIIME 2 2022.11. This is **not well-validated**, so results should be carefully reviewed.

## Installing

In a [QIIME 2](https://qiime2.org) environment (tested with 2022.11), pip install the other dependencies with the requirements file found in this repository (`pip install requirements.txt`). It should work.

## References

The example data included here is from the [Human Microbiome Project (HMP 1)](https://www.hmpdacc.org/hmp/). It was accessed using [Qiita](https://qiita.microbio.me) under study id 1928 in 2022. Differential abundance was computed using [ANCOM-BC](https://www.nature.com/articles/s41467-020-17041-7) via [q2-composition](https://github.com/qiime2/q2-composition).

