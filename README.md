# Baseline solutions for the Online Round of IDAO-2019

`scoring.py` contains an implementation of the quality metric

[`Baseline - simple.ipynb`](https://github.com/yandexdataschool/IDAO-2018-muon-id/blob/master/Baseline%20-%20simple.ipynb) contains a naive xgboost solution

[`Baseline - advanced.ipynb`](https://github.com/yandexdataschool/IDAO-2018-muon-id/blob/master/Baseline%20-%20advanced.ipynb) conains a primer on jagged arrays processing and creates the model file for Track 2

`track_2_baseline` contains example C++ code to be used in Track
2. Run `make all` to build and the `baseline` binary will be accepting
data as `.csv` (not gzipped) at the standard input and writing
predictions to the standard output.