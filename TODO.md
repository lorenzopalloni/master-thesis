# TODO List

> have a look below in the "high priority section"

- propose changes in the title:
    - Tecniche di ottimizzazione di reti neurali per la super risoluzione
    - Optimization techniques for super-resolution deep learning models

- propose changes in the structure:
    Introduction
[not sure]        1.1 Motivation
[not sure]        1.2 Problem Statement
[not sure]        1.3 Objectives and Contributions
[not sure]        1.4 Thesis Outline

    Background
[not sure]        2.1 Literature Review
[not sure]        2.2 State-of-the-Art

    Metrics
[drafted]        3.1 Traditional Metrics
[drafted]        3.2 Perceptual Metrics

    Architectures
[drafted]        4.1 UNet Architecture
[drafted]        4.2 SRUNet Architecture
[drafted]        4.3 Training Setup

    Optimizations
[not sure]        5.1 Overview of Optimization Techniques for Deep Learning-based SR Models
        5.2 Custom Dataloader to Speed up Training
        5.3 TensorRT to Speed up Inference

    Experiments
        6.1 Experimental Setup
        6.2 Results and Analysis
        6.2.1 Quantitative Results
        6.2.2 Qualitative Results
        6.3 Discussion

    Conclusions
[drafted]        7.1 Summary of Contributions
[drafted]        7.2 Limitations and Future Work
[drafted]        7.3 Conclusion


## high priority

- architectures: draft UNet explanation
- architectures: draft SRUNet explanation
- architectures: draft training setup

- optimizations: draft overview optimization techniques
- optimizations: draft custom dataloader section
- optimizations: draft tensorrt section

- experiments: clean up

- code: add VMAF as quality metric for video
- code: train with PNG for ground-truth images
- code: train again replacing LPIPS with another perceptual loss

- bureaucracy about thesis:
    - website
    - a CS professor: ask about supervisor and especially about Leonardo Galtieri
        that should not be able to do as supervisor cause he's an adjunct professor
    - mighelett'
    - emilio

---

## medium priority
- metrics: put some details on some metrics, especially where you have already written something
- metrics: add VMAF description, once you have used it

- code: replace LPIPS with one of the new metrics available in the literature as loss

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
- DONE - metrics: clean up

