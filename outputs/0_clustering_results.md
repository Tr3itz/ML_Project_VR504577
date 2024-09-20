## Input statistics ##
3D Shapes dataset:
-- train: 480000
-- val: 480000

Cluster features of subspace #2
subspace_2.shape: (480000, 10)

## 1 - HDBSCAN ##
Completed HDBSCAN clustering after 75.22330522537231 seconds.
Number of clusters is: 15
Label counts:
[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]
[10479 19200 28800 38400 57600 38400 28801 38384 57596 38354 19199 35890 17105 16154 35638]
Clustering procedure done!
Total runtime: --- 91.47781443595886 seconds ---

## 2 - KMeans (init random) ##
Completed KMeans clustering after 0.6110355854034424 seconds.
Number of clusters is: 15
Label counts:
[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]
[19201 28800 17118 38319 95999 16287 17933 19204 38400 21282 28811 19281 23380 38396 57589]
Clustering procedure done!
Total runtime: --- 16.860557556152344 seconds ---

## 3 - KMeans++ ##
Completed KMeans++ clustering after 1.3325374126434326 seconds.
Number of clusters is: 15
Label counts:
[ 0  1  2  3  4  5  6  7  8  9 10 11 12 13 14]
[38400 38396 28800 57600 57600 38309 38556 19204 19274 38400 38400 19200 19035 19291  9535]
Clustering procedure done!
Total runtime: --- 17.40735387802124 seconds ---

## 4 - MeanShift ##
Starting clustering procedure using MeanShift...
Completed MeanShift clustering after 504.54237484931946 seconds.
Number of clusters is: 2
Label counts:
[0 1]
[240000 240000]
Clustering procedure done!
Total runtime: --- 520.5932312011719 seconds ---
