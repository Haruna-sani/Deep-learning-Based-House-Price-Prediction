# 🏠 House Price Prediction in Norwich using Artificial Neural Networks (ANN)

This project explores the application of Artificial Neural Networks (ANN) to predict house prices in Norwich. The model was trained and evaluated under different hyperparameter configurations to understand their impact on performance, particularly focusing on learning rates and batch sizes.

The training process involved using four different learning rates: **0.0001**, **0.001**, **0.01**, and **0.1**, with an initial batch size of **64**. Among these, the learning rate of **0.001** produced the best result, achieving a maximum **R² value of 0.9422**, indicating strong variance capture and prediction accuracy.

To further assess the model's behavior, different batch sizes were tested under the optimal learning rate of **0.001**. The batch sizes evaluated included **64**, **128**, and **256**. It was observed that the model attained its highest R² value of **0.939** with a batch size of **64**. However, as the batch size increased, the R² values progressively dropped — **0.920** with a batch size of **128**, and **0.832** with **256**.

## 🔍 Key Observations
- The ANN model performed best with a learning rate of **0.001** and a batch size of **64**.
- Increasing the batch size under the same learning rate led to a decline in model performance.
- The results emphasize the importance of hyperparameter tuning in training neural networks for accurate regression tasks.

## 📌 Conclusion
This project demonstrates how careful selection of learning rates and batch sizes can significantly influence model accuracy in real-world prediction problems such as house pricing.

