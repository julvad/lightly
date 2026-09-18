# LightlySSL fork
My fork of https://github.com/lightly-ai/lightly supporting **1-channel inputs and better SAR processing**. 
WIP.




______________________________________

## Lightly FAQ

- Why should I care about self-supervised learning? Aren't pre-trained models from ImageNet much better for transfer learning?

  - Self-supervised learning has become increasingly popular among scientists over the last years because the learned representations perform extraordinarily well on downstream tasks. This means that they capture the important information in an image better than other types of pre-trained models. By training a self-supervised model on _your_ dataset, you can make sure that the representations have all the necessary information about your images.

- How can I contribute?

  - Create an issue if you encounter bugs or have ideas for features we should implement. You can also add your own code by forking this repository and creating a PR. More details about how to contribute with code is in our [contribution guide](CONTRIBUTING.md).

- Is this framework for free?

  - Yes, this framework is completely free to use and we provide the source code. We believe that we need to make training deep learning models more data efficient to achieve widespread adoption. One step to achieve this goal is by leveraging self-supervised learning. The company behind Lightly is committed to keep this framework open-source.

- If this framework is free, how is the company behind Lightly making money?
  - Training self-supervised models is only one part of our solution.
    [The company behind Lightly](https://lightly.ai/) focuses on processing and analyzing embeddings created by self-supervised models.
    By building, what we call a self-supervised active learning loop we help companies understand and work with their data more efficiently.
    As the [Lightly Solution](https://docs.lightly.ai) is a freemium product, you can try it out for free. However, we will charge for some features.
  - In any case this framework will always be free to use, even for commercial purposes.

### Lightly in Research

- [DINOv2-3D: Self-Supervised 3D Vision Transformer Pretraining](https://github.com/AIM-Harvard/DINOv2-3D-Med)
- [Joint-Embedding vs Reconstruction: Provable Benefits of Latent Space Prediction for Self-Supervised Learning, 2025](https://arxiv.org/abs/2505.12477)
- [Reverse Engineering Self-Supervised Learning, 2023](https://arxiv.org/abs/2305.15614)
- [Learning Visual Representations via Language-Guided Sampling, 2023](https://arxiv.org/pdf/2302.12248.pdf)
- [Self-Supervised Learning Methods for Label-Efficient Dental Caries Classification, 2022](https://www.mdpi.com/2075-4418/12/5/1237)
- [DPCL: Contrastive representation learning with differential privacy, 2022](https://assets.researchsquare.com/files/rs-1516950/v1_covered.pdf?c=1654486158)
- [Decoupled Contrastive Learning, 2021](https://arxiv.org/pdf/2110.06848)
- [solo-learn: A Library of Self-supervised Methods for Visual Representation Learning, 2021](https://www.jmlr.org/papers/volume23/21-1155/21-1155.pdf)
- [EdgeCrafter: Compact ViTs for Edge Dense Prediction via Task-Specialized Distillation](https://arxiv.org/pdf/2603.18739)
- [Unlabeled to Accurate: Self-Supervised Learning for Land Use Classification in Sentinel-2 Imagery](https://ieeexplore.ieee.org/abstract/document/11087068)
- [Self-supervised Representation Learning for AI-Based Musculoskeletal Radiograph Registry Construction](https://link.springer.com/chapter/10.1007/978-3-032-14492-8_29)
- [Real-Time Object Detection Meets DINOv3](https://intellindust-ai-lab.github.io/projects/DEIMv2/)
- [Vision Foundry: A System for Training Foundational Vision AI Models, 2025](https://arxiv.org/pdf/2512.11837)
- [Self-supervised learning outperforms supervised learning for crop classification by annotating only 5% of images, 2025](https://link.springer.com/article/10.1007/s11119-025-10302-9)
- [Self-Supervised Learning Powered by Synthetic Data From Diffusion Models: Application to X-Ray Images, 2025](https://doi.org/10.1109/ACCESS.2025.3555619)
- [Wildlife Target Re-Identification Using Self-supervised Learning in Non-Urban Settings, 2025](https://arxiv.org/pdf/2507.02403)
- [SSL-MAE: Adaptive Semisupervised Learning Framework for Multilabel Classification of Remote Sensing Images Using Masked Autoencoders, 2025](https://ieeexplore.ieee.org/document/11029124/)

### Company behind this Open Source Framework

[Lightly](https://www.lightly.ai) is a spin-off from ETH Zurich that helps companies
build efficient active learning pipelines to select the most relevant data for their models.

You can find out more about the company and it's services by following the links below:

- [Homepage](https://www.lightly.ai)
- [LightlyTrain](https://docs.lightly.ai/train/stable/index.html)
- [Web-App](https://app.lightly.ai)
- [LightlyStudio](https://docs.lightly.ai/studio/)
- [Lightly's AwesomeSSL](https://github.com/lightly-ai/awesome-self-supervised-learning) (collection of SSL papers)

[Back to top🚀](#top)
