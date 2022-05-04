## Reading List

* [1] IJCAI17_Image-embodied Knowledge Representation Learning.
* [2] `EMNLP19_Language Models as Knowledge Bases.`
* [3] `EMNLP20_Transformer Feed-Forward Layers Are Key-Value Memories.`
* [4] ICLR21_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.
* [5] ACL21_Knowledgeable or Educated Guess Revisiting Language Models as Knowledge Bases.
* [6] `ACL22_Knowledge Neurons in Pretrained Transformers.`
* [7] ICLR22_Beit: Bert pre-training of image transformers.
* [8] `CVPR22_Masked Autoencoders Are Scalable Vision Learners.`

## Generative Pretrained Visual Models, with Masked Image Modeling (MIM)

Masked Image Modeling (MIM), inherits the `mask-and-reconstruct` thought from masked autoencoding methods in NLP field, such as [BERT](https://github.com/google-research/bert). More concretely, parts of content in input image are masked to learn latent representations from the visible regions by encoder, which are then used to reconstruct content by decoder.

Method|Conference|Title|Code
-----|-----|-----|-----
iGPT|ICML 2020|[Generative Pretraining from Pixels](http://proceedings.mlr.press/v119/chen20s/chen20s.pdf)|[iGPT](https://github.com/openai/image-gpt)
SiT|Arxiv 2021|[SiT: Self-supervised vIsion Transformer](https://arxiv.org/pdf/2104.03602.pdf)|[SiT](https://github.com/Sara-Ahmed/SiT)
MST|NeurIPS 2021|[MST: Masked Self-Supervised Transformer for Visual Representation](https://arxiv.org/pdf/2106.05656.pdf)|None
BEiT|ICLR 2022|[BEiT: BERT Pre-Training of Image Transformers](https://arxiv.org/abs/2106.08254)|[BEiT](https://github.com/microsoft/unilm/tree/master/beit)
MAE|CVPR 2022|[Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/pdf/2111.06377.pdf)|[MAE](https://github.com/facebookresearch/mae)
iBoT|ICLR 2022|[iBOT: Image BERT Pre-Training with Online Tokenizer](https://arxiv.org/pdf/2111.07832.pdf)|[iBoT](https://github.com/bytedance/ibot)
SimMIM|Arxiv 2021|[SimMIM: A Simple Framework for Masked Image Modeling](https://arxiv.org/pdf/2111.09886.pdf)|[SimMIM](https://github.com/microsoft/SimMIM)
PeCo|Arxiv 2021|[PeCo: Perceptual Codebook for BERT Pre-training of Vision Transformers](https://arxiv.org/pdf/2111.12710.pdf)|None
ADIOS|Arxiv 2022|[Adversarial Masking for Self-Supervised Learning](https://arxiv.org/pdf/2201.13100.pdf)|None
CAE|Arxiv 2022|[Context Autoencoder for Self-Supervised Representation Learning](https://arxiv.org/pdf/2202.03026.pdf)|None
CIM|Arxiv 2022|[Corrupted Image Modeling for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2202.03382.pdf)|None
AttMask|Arxiv 2022|[What to Hide from Your Students: Attention-Guided Masked Image Modeling](https://arxiv.org/pdf/2203.12719.pdf)|None
mc-BEiT|Arxiv 2022|[mc-BEiT: Multi-choice Discretization for Image BERT Pre-training](https://arxiv.org/pdf/2203.15371.pdf)|None
