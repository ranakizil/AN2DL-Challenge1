# First Challenge of the PoliMi course of Artificial Neural Networks and Deep Learning, 2025

## Multivariate Time Series Classification on Pirate Pain Levels

In this challenge, we tackled a **multivariate time series classification task** to predict pain levels (**no pain**, **low pain**, **high pain**) from 180-step sequential data comprising body joints, survey metrics, and metadata. By experimenting with preprocessing, rebalancing, and a custom **1D CNN + BiLSTM** model, we identified our best-performing approach (`03_SMOTE_Only`). Utilizing standard scaling, SMOTE, and a macro F1 callback, this streamlined model outperformed more complex configurations, achieving an impressive validation macro F1-score of **0.9681** and a weighted F1-score of **0.9834**.
