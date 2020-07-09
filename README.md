# AFM
novel deep learning application for prediction of CNTs-modified asphalt’s adhesion force.

This project is implemented in Keras. The steps applied are:

1.  Data preprocessing: The data need to be normalized within the scale of the activation function used by the network.
2. Develop CNN model
3. Network parameters need to be specified: Batch size Number of neurons Number hidden layer Optimizer Loss function Number of iteration (epoch)
4. Validate model : A testing data set will be used to evaluate network performance.
5. Sensityvity Analysis: Sensitivity analysis, a useful tool, determine the importance of the independent variables. The most sensitive factors affecting the adhesion force 1DCNN is analyzed by the permutation importance with Eli5 python package. Based on the concepts of the permutation importance method, the sensitivity for each independent component can be determined through establishing the degree of the relationship between the adhesion force and the considered independent component.
