# Linear Attention Vision Transformers for End-to-End Mass Regression and Classification

This repository implements the ML4SCI GSoC project:

Linear attention vision transformers for end-to-end mass regression and classification.

Goal:
Train a linear attention vision transformer on particle collision detector images to perform:

1. Particle mass regression
2. Particle type classification

Pipeline:

1. Pretrain Vision Transformer on unlabeled dataset
2. Finetune on labeled dataset
3. Compare:
   - pretrained model
   - model trained from scratch

Datasets:

Unlabeled dataset:
Dataset_Specific_Unlabelled.h5

Labeled dataset:
Dataset_Specific_labelled_full_only_for_2i.h5

Model:

Linear Attention Vision Transformer based on Cross-Covariance Attention (XCA).

Framework:
PyTorch

Notebook implementation located in:
notebooks/linear_attention_vit.ipynb
