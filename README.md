# IS604

All of the volatility-normalized data and code used to generate this paper is available under the following github repository.

https://github.com/dgn2/IS604

The repository includes Python code used to both fetch data from Bloomberg (i.e., monthly S&P500 index constituent, daily price, dividend, and split data) and perform the volatility normalization.

The repository also includes the R/C++ source file implementing the simple trading model, and the .Rmd file used to generate the paper. The simulations have been disabled with the .Rmd file by setting the 'eval' flag to FASLE. To run the .Rmd, a significant amount of RAM is required

The simulation was run on a recent quad-core workstation with 64 gigs of RAM. 