# k-means-without_library
Write a program to implement the k-means algorithm. Randomly select the initial centroids. The
program will take two inputs: a data file (data.csv) containing multiple (at least 3) continuous
features and a value for k. Your program will load the data file and then apply the k-means
algorithm. The clustering process will continue until cluster-assignments/centroids do not change
or a maximum of 100 iterations have been completed. The program will add a new column
containing cluster ids (1, 2, 3, …, k) to the original input file and save it to clustered_data.csv,
where k is the number of clusters. You are allowed to use a library for distance calculation and
handling data files. However, you cannot use any library for clustering.
