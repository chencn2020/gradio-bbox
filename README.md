# Gradio-BBox

<img src="https://github.com/chencn2020/SEAGULL/raw/main/imgs/Logo/logo.png" alt="SEAGULL" style="height: auto; width: 100%; margin-bottom: 3%;">

It is an extension to official [gradio-3.36.1](https://github.com/gradio-app/gradio), which supports **drawing boxes** on top of an image. 

This repository is forked from [Gradio-Osprey-Demo](https://github.com/LiWentomng/gradio-osprey-demo).

Thanks for their great contribution.

## Install

### 1. Install Node.js

We install it on Ubuntu with:

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

source ~/.bashrc # or ~/.zshrc based on which one you use

nvm install v18.16.0
```


### 2. Install ppnm

```
curl -fsSL https://get.pnpm.io/install.sh | sh -

source ~/.bashrc # or ~/.zshrc based on which one you use

pnpm --version  # check if success
```

### 3. Install gradio

```
git clone https://github.com/chencn2020/gradio-bbox.git

cd gradio-bbox

bash scripts/build_frontend.sh

pip install -e .
```
