TODO List
==========

> pay attention: you should be in another branch called dev
> implement a custom PyTorch Dataset in ./code/copying.py
> remember to activate thesis (define which venv tool to use)

## high priority

- files in fast-sr-unet project:
    - data\_loader.py
    - evaluate\_model.py
    - models.py
    - pytorch\_unet.py
    - render.py
    - train.py
    - utils.py
- study them and identify a good start for studying and copying/adapting

- in fast-sr-unet/evaluate\_mode.py there is a ~260-lines-of-code function really messed up that can be useful as a reference to evaluate different metrics on low vs high quality videos
- start packaging the ./code/ folder in another repo
    - add tests/ and \<package-name\>/ folders to the new repo
    - manage it with poetry
    - poetry vs conda: understand which one would be the best to manage the venv for the project

- pytorch dataset

- look for LPIPS-Comp
- look for LPIPS
- look for SSIM / MS-SSIM

- binarize SR-UNet

---

## medium priority
- remember to use Hydra
- Comet.ml was suggested by the professor
- sync GitHub and Overleaf

---

## low priority

---
#### Streak
May 8-27  # 19 days
May 30

#### DONEs
- DONE - .gitignore literature/ folder, plus Python and LaTex stuff
- DONE - set up abstract
- DONE - simple makefile
- DONE - understand bibliography
- DONE - sync between local and Onyx files
- DONE - overleaf setup
- DONE - init git repo for the thesis
- DONE - convert sh script for video preparation to Python
