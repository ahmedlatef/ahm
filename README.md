# Steps :
Divide the array into the number of blocks known as run.
Consider size of run either 32 or 64(in the below implementation, size of run is 32.)
Sort the individual elements of every run one by one using insertion sort.
Merge the sorted runs one by one using merge function of merge sort.
Double the size of merged sub-arrays after every iteration.
