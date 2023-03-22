# ControlNet

## Source

```bash
https://github.com/lllyasviel/ControlNet
```

## Download

download from

```bash
https://huggingface.co/lllyasviel/ControlNet/tree/main
```

and make sure it looks like

```bash
--models/
  |--control_sd15_*.pth
--annotator/ckpts/
  |--<other-models>.pth
```

## Install

```bash
conda create -n control python=3.8
conda activate control
./setup.sh
```

## Run

```bash
python gradio_*.py
```

## Enjoy it~
