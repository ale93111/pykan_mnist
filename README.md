## Kolmogorov Arnold Networks trained on MNIST 

From (https://github.com/KindXiaoming/pykan)[https://github.com/KindXiaoming/pykan] 
Kolmogorov-Arnold Networks (KANs) are promising alternatives of Multi-Layer Perceptrons (MLPs). KANs have strong mathematical foundations just like MLPs: MLPs are based on the universal approximation theorem, while KANs are based on Kolmogorov-Arnold representation theorem. KANs and MLPs are dual: KANs have activation functions on edges, while MLPs have activation functions on nodes. This simple change makes KANs better (sometimes much better!) than MLPs in terms of both model accuracy and interpretability.

In this repo KANs are trained on the popular MNIST dataset. While this project was very easy to implement it was still interesting to test such a novel architecture which is gaining a lot of popularity.

Conclusions:
 - the implementation is still very inefficient, training on the entire MNIST dataset requires 200+ GB of RAM so this is why i used only 30% of the dataset
 - Final accuracy on the test set 90%, which i think is a nice result 
 - In very few epochs it achieves 100% on the training set
