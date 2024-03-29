# Federated-Learning
Federated Learning allows training high-level machine learning models with user’s data without the data 
leaving the edge device. This allows Federated Learning (FL) models to create better-personalized results for the user’s community. As Federated Learning is fairly new, it is susceptible to data leakage or even data manipulation by attackers. The architecture of FL is an Iterative process, hence even a small 
data manipulation can lead to exploding errors. The main aim of Federated Learning is to keep the user’s data on the edge device. This is achieved by sending the base Machine Learning model to the edge device and training the models on the user’s data, then weights and biases of these trained models are sent to the “Access Layer” at the server end which collects these parameters from all the devices on the FL network. By this, the data is not actually sent to the server but the model learns the weights & biases. Considering the high risk of data manipulation through cyberattacks, the approach of the study in this paper is to learn about data integrity in transit in Federated Learning wherein the different types of cyberattacks have been explored and activity attack modeling has been done on federated learning architecture. Conclusive remarks have been presented along with different characteristics and behavioral properties of various cyber attacks

<img src="https://1.bp.blogspot.com/-K65Ed68KGXk/WOa9jaRWC6I/AAAAAAAABsM/gglycD_anuQSp-i67fxER1FOlVTulvV2gCLcB/s640/FederatedLearning_FinalFiles_Flow%2BChart1.png">

## Paper Status
- __`Accepted at IEEE WIECON 2022`__
