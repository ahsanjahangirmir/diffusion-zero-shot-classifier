In this repository, I explore how text-to-image diffusion models, specifically Stable Diffusion, can be repurposed for zero-shot classification tasks without any additional training. The core idea[1] is that these models, trained to generate images conditioned on text, inherently learn a joint representation of images and textual concepts. By leveraging the denoising process in the latent space and measuring the alignment between an input image and various textual categories, we can classify images in a zero-shot manner.

*Resources:*

- [1][K. Clark and P. Jaini. Text-to-image diffusion models are zero-shot classifiers, 2023](https://arxiv.org/pdf/2303.15233)
- [Stable Diffusion Deep Dive](https://github.com/fastai/diffusion-nbs/blob/master/Stable%20Diffusion%20Deep%20Dive.ipynb)
- [Diffusers Library Documentation (HuggingFace)](https://huggingface.co/docs/diffusers/index)
