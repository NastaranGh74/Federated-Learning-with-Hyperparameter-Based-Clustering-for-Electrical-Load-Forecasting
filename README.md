# Federated-Learning-with-Hyperparameter-Based-Clustering-for-Electrical-Load-Forecasting
This code uses federated learning to forecast electrical power consumption of households while protecting user data privacy. Please refer to the [full paper](https://www.sciencedirect.com/science/article/abs/pii/S2542660521001104) for more information.

Electrical load prediction has become an essential aspect of power system operation, and deep learning models have gained popularity in this area. However, achieving accurate predictions with these models requires large amounts of training data. Unfortunately, sharing individual household electricity consumption data for load prediction raises concerns about user privacy and can be resource-intensive in terms of communication. To address these challenges, edge computing methods like federated learning are gaining significance. These methods enable leveraging data without the need for centralized storage. In this research paper, the performance of federated learning for short-term forecasting of both individual house loads and aggregate load is evaluated. A comparison is made between federated learning and centralized and local learning schemes to highlight their respective advantages and disadvantages. Additionally, a novel client clustering method is proposed to reduce the convergence time of federated learning. The study reveals that federated learning exhibits strong performance, achieving a minimal root mean squared error (RMSE) of 0.117 kWh for individual load forecasting [[1]](#1).



## References
<a id="1">[1]</a> 
Nastaran Gholizadeh, Petr Musilek,
Federated learning with hyperparameter-based clustering for electrical load forecasting,
Internet of Things,
Volume 17,
2022,
100470,
ISSN 2542-6605.
