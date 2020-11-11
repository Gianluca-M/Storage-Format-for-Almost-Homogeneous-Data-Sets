# Storage Format for Almost-Homogeneous Data Sets

Bachelor Thesis by Gianluca Moro

## Links
[Text](https://doi.org/10.3929/ethz-b-000426097)

[Python implementations](https://doi.org/10.3929/ethz-b-000429710)


## Abstract

JSON is a popular data format which is very flexible since no schema needs to be defined and therefore the data can also be heterogeneous. But this flexiblity comes at the price of performance. However, in practice, most data sets do not use the flexibilty of JSON to its full extend and are mostly homogeneous. We call such data sets almost-homogeneous. For almost-homogeneous data sets, the trade-off between the flexibilty and performance loss of JSON is not justified. 

Thus, we propose a new storage format for almost-homogeneous data sets which allows for faster processing by storing the data in the Parquet file format. Parquet is optimized for structured, homogeneous data sets and allows for significantly faster data processing compared to unstructured JSON. 

In this thesis, we first cover the background on Parquet and also analyse the almost-homogeneity in real-life JSON data sets. We then show how to preprocess and convert data sets from JSON to the Parquet format. Finally, we evaluate the processing performance of our new storage format
