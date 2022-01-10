# **GANfolk: Using AI to create portraits of fictional people to sell as NFTs**
## How to use GPT-3, StyleGAN2, and VQGAN to synthesize diverse characters from open-source images

By Robert. A Gonsalves</br></br>
<a href="https://opensea.io/collection/ganfolk">![sample images](https://raw.githubusercontent.com/robgon-art/GANfolk/main/GANfolk%20rect.png)</a>

You can see my article on [Medium](https://towardsdatascience.com/ganfolk-using-ai-to-create-portraits-of-fictional-people-to-sell-as-nfts-6e24f5214ed1) and check out the results here, [opensea.io/collection/ganfolk](https://opensea.io/collection/ganfolk)

The source code and generated images are released under the [CC BY-SA license](https://creativecommons.org/licenses/by-sa/4.0/).</br></br>
**If you use this project to create images, please give attribution like this:** This image was created with [GANfolk](https://opensea.io/collection/ganfolk) by [Robert A. Gonsalves](https://robgon.medium.com/).</br></br>
![CC BY-NC-SA](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

## Google Colabs
* [GANfolk - StyleGAN 2 and CLIP](https://colab.research.google.com/github/robgon-art/GANfolk/blob/main/GANfolk_StyleGAN_2_and_CLIP.ipynb)
* [GANfolk - VQGAN and CLIP](https://colab.research.google.com/github/robgon-art/GANfolk/blob/main/GANfolk_VQGAN_and_CLIP.ipynb)

## Acknowledgements
* StyleGAN 2 by T. Karras, et al., [Analyzing and Improving the Image Quality of StyleGAN](https://arxiv.org/pdf/1912.04958.pdf)</br>
* StyleGAN 2 implementation by rosinality, https://github.com/rosinality/stylegan2-pytorch</br>
* VQGAN by P. Esser, R. Rombach, and B. Ommer, [Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/pdf/2012.09841.pdf)</br>
* CLIP by A. Radford, et al., [Learning Transferable Visual Models From Natural Language Supervision](https://medium.com/r/?url=https%3A%2F%2Fcdn.openai.com%2Fpapers%2FLearning_Transferable_Visual_Models_From_Natural_Language_Supervision.pdf)</br>
* GPT-3 by Tom B. Brown, et al., [Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf)
* The original VQGAN+Clip notebook was made by [Katherine Crowson](https://github.com/crowsonkb), with further modifications by [Justin John](https://colab.research.google.com/github/justinjohn0306/VQGAN-CLIP/blob/main/VQGAN%2BCLIP_%28z%2Bquantize_method_with_augmentations%2C_user_friendly_interface%29.ipynb#scrollTo=c3d7a8be-73ce-4cee-be70-e21c1210a7a6)
