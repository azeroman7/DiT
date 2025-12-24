# Diffusion Models
This repository contains implementations of DiT (Scalable Diffusion Models with Transformers)

## Git clone
from Jourdan's gitHub: https://github.com/Jrampoldi/DiT

```bash
git clone https://github.com/azeroman7/DiT.git
```

## Install Environment via Anaconda (Recommended)
```bash
cd DiT
conda env create -f environment.yml
conda activate DiT
```

## Run Script --> results will be *.png at the ./
For 512x512 image with seed 1
```bash
./run1.sh
```

For 256x256 image with seed 2, num-sampling-steps 500, and cfg-scale 1.0
```bash
./run2.sh
```

## Troubleshoot
This will cover most issues that may occur
```bash
pip uninstall torch torchvision torchaudio
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
conda install python=3.10
pip install diffusers
pip install timm
```


