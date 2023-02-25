Make sure you install PyTroch compiled for CUDA
pip3 install torch==1.12.1+cu116 torchvision==0.13.1+cu116 torchaudio==0.12.1+cu116 -f https://download.pytorch.org/whl/cu116/torch_stable.html

In order to generate images from text (example):
- Astronaut riding a horse
python scripts/txt2img.py --prompt "a photograph of an astronaut riding a horse"


- White sports car
python scripts/txt2img.py --prompt "A white sports car"