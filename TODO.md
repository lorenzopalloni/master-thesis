# TODO List
> resume from code

## Structure
1. Introduction
 - [editable] - introduction

2. Background
 - [to be drafted] - literature review in video restoration

3. Metrics
 - [drafted] - 3.1 Traditional Metrics
 - [drafted] - 3.2 Perceptual Metrics

4. Architectures
 - [drafted] - 4.1 UNet Architecture
 - [drafted] - 4.2 SRUNet Architecture
 - [drafted] - 4.3 Training Setup

5. Optimizations
 - [drafted] - 5.1 Quantization
 - [drafted] - 5.2 TensorRT to Speed up Inference
 - [maybe to be moved, but where?] 5.3 Custom Dataloader to Speed up Training

6. Experiments
 - [editable] - 6.1 Quantitative Results
 - [to be drafted] - 6.2 Qualitative Results

7. Conclusions
 - [editable] - conclusions

## high priority
- [background] make it editable

- [metrics] explain VMAF
- [metrics] explain IQA vs VQA
- [metrics] make it editable
- [metrics] put some technical details on some metrics

- [architectures] make it editable
- [optimizations] make it editable

- [code] run quantitative evaluations
- [code] run quantitative evaluations
- [experiments] include new quantitative evaluations
- [experiments] include new qualitative evaluations
- [experiments] draft qualitative results section

- [optimizations] draft custom dataloader section

## medium priority
- [code] rename the codebase (suggestions: quant)
- [code] handle the gifnoc package (rename, refactor, then publish on PyPI)

## low priority
- [background] add citations
- find a quote

### Comments

## DONEs
- DONE - .gitignore literature/ folder, plus Python and LaTex stuff
- DONE - set up abstract
- DONE - simple makefile
- DONE - understand bibliography
- DONE - sync between local and Onyx files
- DONE - overleaf setup
- DONE - init git repo for the thesis
- DONE - convert sh script for video preparation to Python
- DONE - poetry vs conda: understand which one would be the best to manage the venv for the project
- DONE - study fast-sr-unet repo identifying from which file(s) to start copying/adapting
- DONE - start packaging the ./code/ folder in another repo
- DONE - explain PSNR
- DONE - explain SSIM
- DONE - explain MS-SSIM
- DONE - explain LPIPS-Comp / LPIPS
- DONE - add in README.md how to compile and run latex sources to generate a .pdf
- DONE - study literature in quantization theory
- DONE - give more structure to the thesis
- DONE - [metrics] clean up
- DONE - [architectures] draft UNet explanation
- DONE - [architectures] draft SRUNet explanation
- DONE - [architectures] draft training setup
- DONE - [optimizations] draft overview optimization techniques
- DONE - [optimizations] draft tensorrt section
- DONE - [experiments] clean up
- DONE - [bureaucracy] website
- DONE - [bureaucracy] ask mighelett'
- DONE - [bureaucracy] ask emilio
- DONE - [bureaucracy] ask about supervisors
- DONE - [code] add VMAF as quality metric for video
- DONE - [code] train with PNG for ground-truth images
- DONE - [bureaucracy] ask administration about taxes
- DONE - [introduction] make it editable
- DONE - [conclusions] make it editable by the prof

