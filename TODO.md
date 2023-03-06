# TODO List

## high priority
- propose a change in the title:
    - Tecniche di ottimizzazione di reti neurali per la super risoluzione
    - Optimization techniques of deep learning models for super-resolution

- add VMAF as quality metric for video
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

