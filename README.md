This GitHub organization is dedicated for HKUST COMP 4981 Final Year Project (2023-24): Learned Indexes for Commercial Databases. Refer to our final report [here](https://github.com/hkust-comp4981-di2-2023/README/blob/main/Learned%20Indexes%20for%20Commercial%20Databases.pdf).

## Project Description
The rapid advancement of artificial intelligence and deep learning has significantly impacted various industries and domains. One such domain is the field of databases, where researchers are actively exploring innovative ways to improve the query and write speed. One promising approach is to integrate learning algorithms into indexes (learned indexes). Moreover, the emergence of big data raises the need of high frequency data storage and retrieval, fostering the development of approaches that can increase data throughput of the databases. In recent literature, learned index algorithms and structures have been proposed.

In this project, we have designed and implemented a learned index called Sherry in RocksDB utilizing error-bounded Piecewise Linear Regression (PLR) algorithms. After successfully migrating Sherry into existing RocksDB, we run the stress test and performance benchmark under the newly proposed algorithms. Sherry outperforms the conventional index by saving up to 30% of space.

## Repositories
The major repositories developed in our project include:
- `rocksdb`: RocksDB and implementation of Sherry. Refer to the branch `fyp-6.8.fb-dev-debug` for more.
- `plr-cpp`: A submodule within `rocksdb` encapsulating PLR algorithms.
- `space-test-repo`: A module responsible for benchmarking space consumption of Sherry and the traditional index block.
