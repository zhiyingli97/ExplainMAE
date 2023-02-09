# ExplainMAE
Model Explanation for Masked Autoencoders

## Introduction
+ Implement model explanation methods (saliency, GradCAM and deeplift) and use them on MAE, to visualize the informative patches used in the decision process of ViT.
+ Apply model explanation methods for MAE on both normal data and medical data, achieving the diversity of downstream tasks.
+ We found MAE with finetuned adapted can achieve better interpretability on medical images than normal images.
+ ML Model Explanation (Python, TensorFlow, Captum)

## Files:
- Simulation Code (Jupyter Notebook)
- Report
- Presentations

## Introduction
Masked autoencoders (MAE) are scalable vision learners, suggesting that self-supervised learning (SSL) in vision might embark on a similar trajectory as in NLP. The generative-based SSL model can perform extremely well on downstream tasks, for both vision~(e.g. MAE) and language~(e.g. BERT). Although it can achieve promising few-shot/zero-shot performance for downstream tasks, few works focus on the interpretability and the inner decision process of large-scale pretrained models.

In this report, we first introduce the overall architecture of MAE, and review the existing methods for model explanation. Then, we apply the model explanation methods for MAE with a finetuned adapter via the downstream datasets. Our experimental results and analysis will be presented in the last section.
