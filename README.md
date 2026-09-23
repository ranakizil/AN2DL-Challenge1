# Multivariate Time Series Pain Level Classification

Time series classification model built for the AN2DL Challenge at Politecnico di Milano. The goal is to predict human pain levels (No Pain, Low Pain, High Pain) from 160-step sequences of joint angles, survey indicators, and static features.

## Overview

- **Architecture:** Compact 1D CNN + BiLSTM hybrid trained from scratch.
- **Class Imbalance:** Applied SMOTE on flattened sequence features to handle minority class distribution.
- **Preprocessing:** Cleaned missing values, aggregated static features, and standardized joint motion sequences.
- **Results:** Evaluated 25 setups, achieving a peak validation macro F1-score of **0.968** with the `03_SMOTE_Only` configuration.

## Team

Merve Rana Kızıl, Selahattin Cem Öztürk, İsmail Emre Gümüş, Emre Evcin
