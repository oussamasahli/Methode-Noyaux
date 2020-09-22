# Google-Places-API-Paris-Points-of-Interests-Histogram-method-Kernel-method
The density estimation algorithms are taken in hand. We choose a type of POI to be processed, the objective is to estimate the geographical density law p(x, y) of the POIs in Paris. (x, y are the GPS coordinates of a location). The following two algorithms are studied: - Histogram method. - Kernel method (Parzen, Gaussian). For each of the experiments, we visualize the results obtained by discretization of space and by evaluating in each box the density given by your models (the histogram method). gives directly the discretization to be used). We experiment with different settings. The following questions have been considered: - What happens for low/high discretization for the histogram method? - What is the role of kernel method settings? - How can the best parameters be chosen automatically? - The related question: How to estimate the quality of your model? Next, we compared the density of the different types of POI.  We were also interested in a classification problem which consists in predicting the score of a POI according to its location. In this last context of supervised classification, we put implements the estimator of Nadaraya-Watson and the k-nearest neighbors.  
