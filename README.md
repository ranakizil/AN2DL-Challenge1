# Challenges of the PoliMi course of Artificial Neural Networks and Deep Learning, 2025

## Challenge 1: Multivariate Time Series Classification on Pirate Pain Levels

In this challenge, we tackled a **multivariate time series classification task** to predict pain levels (**no pain**, **low pain**, **high pain**) from 180-step sequential data comprising body joints, survey metrics, and metadata. By experimenting with preprocessing, rebalancing, and a custom **1D CNN + BiLSTM** model, we identified our best-performing approach (`03_SMOTE_Only`). Utilizing standard scaling, SMOTE, and a macro F1 callback, this streamlined model outperformed more complex configurations, achieving an impressive validation macro F1-score of **0.9681** and a weighted F1-score of **0.9834**.

## Challenge 2: Histological Image Classification & Omni-Ensemble

In this challenge, we tackled an image classification task to categorize histopathological breast cancer tissue samples into four clinical subtypes (**HER2(+), Luminal A, Luminal B, and Triple Negative**). Facing real-world challenges like background noise, visual artifacts, and limited data, we adopted a data-centric preprocessing approach utilizing smart cropping and high-resolution training alongside heavy data augmentation. By building an Omni-Ensemble that aggregates predictions across 23 diverse models from the EfficientNet, ResNet, ResNeXt, and DenseNet families—combined with 8-view test-time augmentation—our approach successfully maximized generalization.
