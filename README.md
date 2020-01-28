# EC3 Graph-based Consensus Maximization among Multiple Supervised and Unsupervised Models


The EC3 algorithm is a graph based maximization problem that deals with the meta output data of different classification algorithms. The baseline model that we choose to compare the algorithm against is BGCM, which is a model similar to the above algorithm. 
The new algorithm deals with a method proposed in the paper (Combination of Classification and Clustering Results with Label Propagation) for finding the bi-stochastic matrix from the given co-occurrence and membership matrix that we initially take as the input. 
Also we padded the Yg matrix that represents the probability distribution of Groups belonging to a particular class. We also did checks on the condition of Fo, Fg so that they should adhere to the bi-stochastic nature of the algorithm. We also did some pre-processing on the initial machine learning datasets to produce better results.



