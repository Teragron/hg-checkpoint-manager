# hf-checkpoint-manager

This repository contains scripts and utilities for managing checkpoint files from the Hugging Face model repository. It includes tools for downloading, organizing, and uploading checkpoint files, as well as scripts for working with the Hugging Face API to automate these tasks.

## Getting Started

To use the scripts in this repository, you will need to install the following dependencies:

* `huggingface_hub`
* `shutil`
* `slugify`

You can install these dependencies using pip:
```bash
pip install huggingface_hub shutil slugify
```

# Colab (Click image)


<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://colab.research.google.com/drive/1VX4nIDcfgQh0tGp64Ygkk6Fti6Zi9Udq?usp=sharing">
<img src='https://github.com/Teragron/hg-checkpoint-manager/blob/main/preview.png'>
</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;







## Usage

To use the scripts in this repository, you will need to provide your own Hugging Face API access token. You can obtain a token by following the instructions [here](https://huggingface.co/docs/hub/security-tokens)

Once you have your access token, you can use the scripts in this repository to perform various tasks, such as downloading a checkpoint file from the Hugging Face model repository or uploading a checkpoint file to a new repository.

# Note
A lot of code bits for this script are taken from TheLastBen Repo for stable diffusion:
https://github.com/TheLastBen/fast-stable-diffusion
