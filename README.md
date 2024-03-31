The total architecture is called Vision Transformer (ViT in short). Let’s examine it step by step.
- Split an image into patches
- Flatten the patches
- Produce lower-dimensional linear embeddings from the flattened patches
- Add positional embeddings
- Feed the sequence as an input to a standard transformer encoder
- Pretrain the model with image labels (fully supervised on a huge dataset)
- Finetune on the downstream dataset for image classification

![image](https://github.com/vnlvi2k3/ViT/assets/139733764/a3159668-a944-4f6b-ba66-603a9653d37e)
