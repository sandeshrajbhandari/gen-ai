# Gen AI for image

This is a barebones repo I made for my future reference. This repo should have basic inference notebooks, notebook for training and a section with a list of community demos and showcases I've discovered.

Hopefully this will be a living document, updated throughtout time as the field develops.

## Different ways to use Stable diffusion

1. Diffusers library
2. Kohya GUI
3. [AUTOMATIC1111 UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) [Tutorial](https://stable-diffusion-art.com/automatic1111/)
4. [ComfyUI](https://github.com/comfyanonymous/ComfyUI)

I'm using online cloud gpus from colab and kaggle, and colab recently banned automatic1111 web uis. I haven't tried any workarounds yet. So, I'm focusing on writing code using diffusers library. However, I've to reinvent the wheel for features that are already better implemented in Kohya and Automatic1111 web uis for training and inference.

Other resources for high quality tutorials include guides in civitAI and reddit posts on stable diffusion subreddit.

## Stable Diffusion

- SDXL

  - SDXL Basic inference

- SDXL addons
  - LCM - fast inference in few steps (4-6 steps)
  - LORA - for training on images.

Hopefully every point is updated as I go through learning more about them. This repo will heavily rely on diffusers documentation by huggingface as a starting point with a few more code to download datasets and models from public sites like civitAI.
