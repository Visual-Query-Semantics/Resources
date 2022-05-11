## Reading List

* [01] CVPR14_Cross-Scale Cost Aggregation for Stereo Matching.
* [02] NeurIPS17_`Attention Is All You Need.`
* [03] IJCAI17_Image-embodied Knowledge Representation Learning.
* [04] Blog19_[Transformer Architecture: The Positional Encoding](https://kazemnejad.com/blog/transformer_architecture_positional_encoding/).
* [05] EMNLP19_`Language Models as Knowledge Bases.`
* [06] AAAI21_`Self-Attention Attribution: Interpreting Information Interactions Inside Transformer.`
* [07] Arxiv19_SPair-71k: A Large-scale Benchmark for Semantic Correspondence.
* [08] ICCV19_Hyperpixel Flow: Semantic Correspondence with Multi-layer Neural Features.
* [09] EMNLP20_`Transformer Feed-Forward Layers Are Key-Value Memories.`
* [10] ICLR21_An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.
* [11] ACL21_Knowledgeable or Educated Guess Revisiting Language Models as Knowledge Bases.
* [12] ACL22_`Knowledge Neurons in Pretrained Transformers.`
* [13] ICLR22_Beit: Bert pre-training of image transformers.
* [14] CVPR22_`Masked Autoencoders Are Scalable Vision Learners.`

## Generative Pretrained Visual Models, with Masked Image Modeling (MIM)

Masked Image Modeling (MIM), inherits the `mask-and-reconstruct` thought from masked autoencoding methods in NLP field, such as [BERT](https://github.com/google-research/bert). More concretely, parts of content in input image are masked to learn latent representations from the visible regions by encoder, which are then used to reconstruct content by decoder. For the downstream visual tasks, the encoder is expected to yield robust representation with `rich semantic information`. Language naturally has semantics highly abstracted by human, where the elemental unit is also discrete. Yet pixels contained in image merely contain low-level statistics and often present the heavy redundancy due to the continuous property of image. So there is a great need for a benchmark to effectively measure whether the pre-trained visual models can present the following properties: 1) well discretizing continuous image content; 2) containing high visual semantic.

Method|Conference|Title|Code
-----|-----|-----|-----
SiT|Arxiv 2021|[SiT: Self-supervised vIsion Transformer](https://arxiv.org/pdf/2104.03602.pdf)|[SiT](https://github.com/Sara-Ahmed/SiT)
MST|NeurIPS 2021|[MST: Masked Self-Supervised Transformer for Visual Representation](https://arxiv.org/pdf/2106.05656.pdf)|None
BEiT|ICLR 2022|[BEiT: BERT Pre-Training of Image Transformers](https://arxiv.org/abs/2106.08254)|[BEiT](https://github.com/microsoft/unilm/tree/master/beit)
MAE|CVPR 2022|[Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/pdf/2111.06377.pdf)|[MAE](https://github.com/facebookresearch/mae)
iBoT|ICLR 2022|[iBOT: Image BERT Pre-Training with Online Tokenizer](https://arxiv.org/pdf/2111.07832.pdf)|[iBoT](https://github.com/bytedance/ibot)
SimMIM|CVPR 2022|[SimMIM: A Simple Framework for Masked Image Modeling](https://arxiv.org/pdf/2111.09886.pdf)|[SimMIM](https://github.com/microsoft/SimMIM)
PeCo|Arxiv 2021|[PeCo: Perceptual Codebook for BERT Pre-training of Vision Transformers](https://arxiv.org/pdf/2111.12710.pdf)|None
MaskFeat|Arxiv 2021|[Masked Feature Prediction for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2112.09133.pdf)|None
CAE|Arxiv 2022|[Context Autoencoder for Self-Supervised Representation Learning](https://arxiv.org/pdf/2202.03026.pdf)|None
AttMask|Arxiv 2022|[What to Hide from Your Students: Attention-Guided Masked Image Modeling](https://arxiv.org/pdf/2203.12719.pdf)|None
mc-BEiT|Arxiv 2022|[mc-BEiT: Multi-choice Discretization for Image BERT Pre-training](https://arxiv.org/pdf/2203.15371.pdf)|None
