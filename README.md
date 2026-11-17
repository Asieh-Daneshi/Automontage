# Automontage

This repository contains a copy of **AOAutomontaging-NEU2019**, a MATLAB toolbox for automatically stitching adaptive optics (AO) retinal images into a montage.

The toolbox is not my own work. It was developed by others and is shared here with its original license and README, which are included in the archive. Please read `LICENSE.md` in the archive before reusing or redistributing anything.

## What is in the repository

| File | Description |
|---|---|
| `AOAutomontaging-NEU2019.rar` | The complete toolbox as a single archive. |

After extracting the archive you get a folder `AOAutomontaging-NEU2019` that contains, among other things:

- `AutoAOMontagingGUI.m` and `AutoAOMontagingGUI.fig`: the MATLAB GUI for running the montaging.
- `SupportFunctions/`: the MATLAB functions behind the GUI (feature matching, position file reading, Photoshop layer helpers), including a bundled copy of VLFeat 0.9.20.
- `Demos/Demo_Instructions.md`: short demos for getting started.
- `AOVISIONLab_Example_Montage/`: example stabilised AOSLO frames with a `PositionFile.xlsx`.
- `Configuration/`: a template for local settings.
- `README.md`, `README_Extension.docx` and `LICENSE.md`: the original documentation and license.

## How to use it

1. Download `AOAutomontaging-NEU2019.rar` and extract it (it needs a tool that can open RAR files).
2. Open MATLAB and run `AutoAOMontagingGUI.m` from the extracted folder.
3. Follow `Demos/Demo_Instructions.md` and the original `README.md` for the inputs the GUI expects.

## Credit

The method behind this toolbox is described in:

M. Chen, R. F. Cooper, G. K. Han, J. Gee, D. H. Brainard and J. I. W. Morgan, "Multi-modal automatic montaging of adaptive optics retinal images," *Biomedical Optics Express* 7(12), 4899-4918 (2016). doi:10.1364/BOE.7.004899

If you use the software in a publication, please cite that paper, and follow the citation request in the original README.
