# The SHAP method for interpretability of decisions on fraud detection obtained from machine learning models

The SHAP method (SHapley Additive exPlaination) is a modern approach for the local interpretation of machine learning models. Based on the Shapley Value, a concept introduced by Lloyd Shapley in 1953 in the field of cooperative game theory, the SHAP method allows each variable used in the training of a machine learning model to be assigned a value (positive or negative) corresponding to its importance in determining a certain result produced by that model. However, the computational complexity of this method grows exponentially as the number of variables used increases and, consequently, its implementation becomes prohibitively expensive for high-dimensional datasets. This has led to the development of approaches aimed at approximating its value while guaranteeing computational efficiency.

The purpose of this thesis is to show how the SHAP method, its extensions and approximation approaches work in relation to the predictions produced by certain machine learning models in the context of financial fraud detection. In doing so, the aim is to show how this method increases the interpretability and thus reliability of these models, as well as verify the computational advantages of its approximation approaches.
