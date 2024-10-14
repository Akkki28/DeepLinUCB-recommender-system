# DeepLinUCB-recommender-system
A recommender system using the contextual bandit solution that integrates Deep Neural Network extracted features into the LinUCB algorithm. This hybrid approach enhances the system’s ability to make decisions by using high-dimensional context vectors from the DNN, thus improving its recommendations in dynamic environments.
![image](https://github.com/user-attachments/assets/1d795978-c74b-41cd-b0be-6be34faf752a)

# Working
This algorithm involves 2 parts, offline and online. The offline part involves training of a DNN on a labeled datsaet.The workfow of offine training is depicted in Algorithm1. Then the DNN model is uploaded and served in the online service. For the online training part, we take the output of DNN as the context feature in LinUCB, and update parameters in LinUCB as shown in Algorithm 2.
![image](https://github.com/user-attachments/assets/9d5dd19d-3f72-4341-9ad9-2ccb3148216f)

# References
[Original Paper](https://dl.acm.org/doi/pdf/10.1145/3543873.3587684)

