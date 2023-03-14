# TODO List

--------------------------------------------------
## Structure

1. Introduction
 - [drafted] - possible outline:
    - Motivation
    - Problem Statement
    - Objectives and Contributions
    - Thesis Outline

2. Background
 - [drafted] - literature review in video restoration

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
 - [drafted] - 6.1 Quantitative Results
 - 6.2 Qualitative Results

7. Conclusions
 - [drafted] - possible outline:
    - Summary of Contributions
    - Limitations and Future Work
    - Conclusion
--------------------------------------------------

## high priority

- [bureaucracy] ask administration about taxes
- [code] add VMAF as quality metric for video
- [code] train with PNG for ground-truth images
- [code] train again replacing LPIPS with another perceptual loss
- [optimizations] draft custom dataloader section

---

## medium priority
- [metrics] put some details on some metrics, especially where you have already written something
- [metrics] add VMAF description, once you have used it

---

## low priority
- [background] add citations
- [background] update content with a recent survey on video reconstruction
- find a quote

---

### Comments

Thesis title:
- Tecniche di ottimizzazione di reti neurali per il miglioramento della qualità visuale
- Optimization techniques of deep learning models for visual quality improvement

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

