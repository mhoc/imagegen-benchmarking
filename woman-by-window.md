**Prompt**

> a beautiful young woman sitting next to a window, sunlight streaming through the blinds, she is looking into the camera, volumetric light, hyperrealistic photograph, shot on film, 4k, hdr, trending on instagram

Generate 4, I pick the best as defined as most accurate to the prompt and most aesthetically pleasing.

## Stable Diffusion

| Characteristic | Value |
|---------|-------|
| Operating System | Windows 11 build 22621 |
| Python | 3.10.11 |
| CPU | AMD Ryzen 7 5800x |
| Memory | 32gb (2x16gb) DDR4-3200 |
| GPU | Nvidia RTX 3070 Ti (8gb vram) |
| GPU Drivers | 527.37 game ready |
| SSD | 2TB Samsung 970evo NVMe PCIe-4 |
| SD | web-ui `22bcc7be428` |

Machine specific parameters: txt2img, euler a 30x steps, 4x1 batches, cfg scale 7, seed -1, restore faces

- sd-v2-0-768-v-ema.ckpt 512x512
- **Time**: 16s

![00006-3453818299](https://user-images.githubusercontent.com/1148452/230783898-025a5e23-3d60-4d84-b7b7-6ea910e47c75.png)

- sd-v2-0-768-v-ema.ckpt 768x768
- **Time**: 54s

![00026-2668227033](https://user-images.githubusercontent.com/1148452/230784707-ee1bc3db-c835-4931-bd33-fc46f9b50bf1.png)

- sd-v2-1_768-v-ema-pruned.ckpt 768x768
- **Time**: 55s

![00031-683849199](https://user-images.githubusercontent.com/1148452/230784825-2e741e13-1128-473c-b410-dfbb5f56081a.png)

- portrait+1.0.safetensors
- **Time**: 17s

![00009-2800553104](https://user-images.githubusercontent.com/1148452/230784358-e103030a-d15d-4130-8121-1b2f4ad83050.png)

- analog-diffusion-1.0.safetensors
- **Time**: 14s

![00014-74427739](https://user-images.githubusercontent.com/1148452/230784417-8c62fea8-3ce6-4455-be54-f895afce5a9e.png)

- openjourney-v4.ckpt
- **Time**: 16s

![00020-2391843248](https://user-images.githubusercontent.com/1148452/230784475-000133f6-1d54-4859-bd68-1460a64aec41.png)

- stylejourney_v10.safetensors
- **Time**: 15s

![00021-496210841](https://user-images.githubusercontent.com/1148452/230784508-779bc94a-2090-4ce4-beb3-8ae329ddf33c.png)

- DiffusionBee 1.5.2
* **Time**: 3m21s

| Characteristic | Value |
|---------|-------|
| Machine | Macbook Air |
| CPU | Apple M2 |
| Memory | 16gb |
| SSD | 1TB |
| SD | DiffusionBee 1.5.2 |
| Model | "Default" |

_Note: M2 is capable of much faster single image gen; around 22s for 1 image. However, I suspect the lack of active cooling in the MBA creates significant thermal throttling after just a few seconds of generation._

![Untitled](https://user-images.githubusercontent.com/1148452/230783625-10d18c42-8da6-4518-aa49-13c324db6f01.png)

## Midjourney 4

| Characteristic | Value |
|---------|-------|
| Model | Midjourney v4 |

* **Time**: 34s (not including upscale)

![mhoc_a_beautiful_young_woman_sitting_next_to_a_window_sunlight__e9611cfa-efc3-4e51-8138-fd264ae25947](https://user-images.githubusercontent.com/1148452/230784197-4a552a32-13f5-40e7-a189-1bedd540aa6f.png)

## Midjourney 5

| Characteristic | Value |
|---------|-------|
| Model | Midjourney v5 |

* **Time**: 54s (not including upscale)

![mhoc_a_beautiful_young_woman_sitting_next_to_a_window_sunlight__9906a8c7-6632-4b4e-8265-22f016ccde4d](https://user-images.githubusercontent.com/1148452/230783732-65e1ad8e-5eb6-4693-915c-e33c31eefb7f.png)

## Midjourney 5.2

| Characteristic | Value |
|----------------|-------|
| Model | Midjourney v5.2 |
| AR | 16:9 |

* **Time**: 53s (not including upscale)

![mhoc_a_beautiful_young_woman_sitting_next_to_a_window_sunlight__841d6224-4eed-47ff-b942-9b4c6faeb566](https://github.com/mhoc/imagegen-benchmarking/assets/1148452/74e2c8e3-7009-4980-bd9d-efce472f18ef)

## DALL-E (2023-12)

- 2023-12-22; I assume DALLE-3 (via ChatGPT+)

> create a photograph of a beautiful young woman sitting next to a window, sunlight streaming through the blinds, she is looking into the camera, volumetric light, hyperrealistic photograph, shot on film, 4k, hdr, trending on instagram

![DALL·E 2023-12-22 19 09 58 - A beautiful young woman sitting next to a window with sunlight streaming through the blinds, creating a volumetric light effect  She is looking direct](https://github.com/mhoc/imagegen-benchmarking/assets/1148452/15e40980-0f35-4df9-80b4-8a54e9524a53)

> create a photograph of a beautiful young woman sitting next to a window, sunlight streaming through the blinds, she is looking into the camera, volumetric light

![DALL·E 2023-12-22 19 12 35 - A photograph of a beautiful young woman sitting next to a window  Sunlight is streaming through the blinds, creating volumetric light around her  She ](https://github.com/mhoc/imagegen-benchmarking/assets/1148452/69832994-c0b4-4443-a534-debc18427484)

## Midjourney 6.0

- 2023-12-21/22 16:9/10 w/ Creative Upscale

> a beautiful young woman sitting next to a window, sunlight streaming through the blinds, she is looking into the camera, volumetric light, hyperrealistic photograph, shot on film, 4k, hdr, trending on instagram --v 6 --ar 16:9

![mhoc_a_beautiful_young_woman_sitting_next_to_a_window_sunlight__efb3cc6d-e460-46a3-88cd-e5e500ef042f](https://github.com/mhoc/imagegen-benchmarking/assets/1148452/365f24ae-509a-4cad-8d02-07b34449e6e1)

> create a photograph of a beautiful young woman sitting next to a window, sunlight streaming through the blinds, she is looking into the camera, volumetric light --v 6.0 --ar 16:10 --style raw

![mhoc_create_a_photograph_of_a_beautiful_young_woman_sitting_nex_5ce27487-b4c1-4b58-9c46-da7c69daf794](https://github.com/mhoc/imagegen-benchmarking/assets/1148452/3d315ca3-e330-4cdb-992d-09f506c13a4b)

