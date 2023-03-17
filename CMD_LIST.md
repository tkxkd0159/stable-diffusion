# Download weights
[link](https://huggingface.co/CompVis/stable-diffusion)

# Guide
```shell
## `--n_samples <n>` is the number of pictures what we would generate

# txt2img
python optimizedSD/optimized_txt2img.py --prompt "a photograph of an astronaut riding a horse" --H 512 --W 512 [--outdir <dirpath>]

# img2img - get image from prior image
## `--strength` is the degree of how dissimilar it is to the original image
python optimizedSD/optimized_img2img.py --prompt "description" --init-img "source image" --strenght <0.0 ~ 1.0> --H 512 --W 512
```
