# Clean Diffusion (WIP)
Clean Diffusion is Latent Diffusion Model made of public domain images (CC-0).

You would download on [Hugging Face](https://huggingface.co/).
If you are Japanese, I recommend Clean Diffusion For Japanese (TBA) instead of Clean Diffusion (For Global). 
The model is more powerful than this global version.

# Note
> With great power comes great responsibility.

If you **CANNOT UNDERSTAND THESE WORDS**, I recommend that **YOU SHOULD NOT USE ALL OF DIFFUSION MODELS** what have great powers.

# Tuning
Clean Diffusion is less powerful than Stable Diffusion.
However, I recommend to tune Clean Diffusion like Stable Diffusion because Clean Diffusion is Apache 2.0 License.
And I repeat the words before I explain the detail.

> With great power comes great responsibility.

Please consider the words before you tune Clean Diffusion.

## Textual Inversion
TBA on Colab.

## Dreambooth on Stable Diffusion
TBA on Colab.

## Imagic Stable Diffusion
TBA on Colab.

## Pure fine-tuning
TBA

# Transparency of Clean Diffusion
I proof that clean diffusion is clean by following explanation.

## Legal information
Clean Diffusion is legal and ethically.

Clean Diffusion is MADE IN JAPAN.
Therefore, Clean Diffusion is subject to [Japanese copyright laws](https://en.wikipedia.org/wiki/Copyright_law_of_Japan).


TBA

## Training Images
TBA

### List of works
- [ArtBench](https://github.com/liaopeiyuan/artbench) (public domain is True)
- Popeye the Sailor Meets Sindbad the Sailor

### Tiny training images
I will open all training images because these images are public domain.
However, these images are huge (70GB+).
Therefore, I will open the tiny version.

TBA

### Training Process of VAE
![gt](images/inputs_gs-000001_e-000000_b-000002.png)
![reconst](images/reconstructions_gs-000001_e-000000_b-000002.png)
![gt](images/inputs_gs-015750_e-000000_b-031500.png)
![reconst](images/reconstructions_gs-015750_e-000000_b-031500.png)

TBA

## Tranning text-image pares
TBA

## Trainning code and config
Please read ldm_files folder. I refer to [stable-diffusion](https://github.com/runwayml/stable-diffusion) while I create these codes and configs.

TBA

# Citations

```bibtex
@misc{rombach2021highresolution,
      title={High-Resolution Image Synthesis with Latent Diffusion Models}, 
      author={Robin Rombach and Andreas Blattmann and Dominik Lorenz and Patrick Esser and Björn Ommer},
      year={2021},
      eprint={2112.10752},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
```bibtex
@article{liao2022artbench,
  title={The ArtBench Dataset: Benchmarking Generative Models with Artworks},
  author={Liao, Peiyuan and Li, Xiuyu and Liu, Xihui and Keutzer, Kurt},
  journal={arXiv preprint arXiv:2206.11404},
  year={2022}
}
```