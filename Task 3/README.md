# TASK 3

We will explain how we are going to transform the data in order to make it useful. The idea is simple: as we have to identify cut-off points within a trajectory, we try to estimate a vector of exponents for each of the trajectories, which we generate through a sliding window. This way, if we estimate by the means of a sliding window of size n, our vector of exponents will have a length 200 – n.
