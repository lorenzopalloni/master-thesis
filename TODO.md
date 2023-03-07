# TODO List

- propose changes in the title:
    - Tecniche di ottimizzazione di reti neurali per la super risoluzione
    - Optimization techniques of deep learning models for super-resolution

- propose changes in the structure:
    1. Introduction
    2. Background
    3. Metrics
    4. Architectures
        - SRUNet
    5. Optimizations
        - Overview optimization techniques for Deep Learning-based SR models
        - Custom dataloader to speed up training
        - TensorRT to speed up inference
    6. Experiments
    7. Conclusions

## high priority
- add VMAF as quality metric for video
- train with PNG for ground-truth images
- train again replacing LPIPS with another perceptual loss

- metrics: clean up
- architectures: draft SRUNet explanation
- optimizations: draft overview optimization techniques
- optimizations: draft custom dataloader section
- optimizations: draft tensorrt section
- experiments: clean up

- bureaucracy about thesis:
    - website
    - a CS professor: ask about supervisor and especially about Leonardo Galtieri
        that should not be able to do as supervisor cause he's an adjunct professor
    - mighelett'
    - emilio

---

## medium priority
- replace LPIPS with one of the new metrics available in the literature as loss
- explain DISTS
- explain ERQAv2.0

---

## low priority
- background: add citations
- background: update content with a recent survey on video reconstruction
- find a quote

---

### Comments

Thesis title:
- Tecniche di ottimizzazione di reti neurali per il miglioramento della qualità visuale
- Optimization techniques of deep learning models for visual quality improvement

Structure:
- Intro
- 1. Literature review about video restoration
    - RSGAN
    - ERSGAN
- 2. IQA/VQA metrics
- 3. SRUNet
    - description UNet / SRUNet
    - code optimization with custom dataloader with buffer to deal with GPU bottleneck
    - TensorRT
- 4. Experiments and Results
- Conclusion

---

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

