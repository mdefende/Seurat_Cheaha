# Seurat_Cheaha
This is compiled version of the R package Seurat usable on the Cheaha computing cluster at UAB. Installing Seurat on the cluster causes numerous issues for many users due to complications with the installed C++ compilers. As opposed to installing the package on your own, you can instead download this repo and extract the packages into your libraries directory.

## Requirements

- Partition: any partition with nodes using Intel CPUs (DO NOT USE ON amd-hdr100).
- R version: R/4.1.0-foss-2018a-X11-20180131-bare

## Installation

Download or clone the repo to your personal space. Move the R packages from the repo into the directory you want to store the Seurat library in. By default, this would be $HOME/R/x86_64-pc-linux-gnu-library/4.1. Seurat should now be available to load into your R environment.
