# nerf

based on: https://github.com/nerfstudio-project/nerfstudio/


conda create --prefix /nfs/scratch_2/koen/nerf python=3.8

conda activate /nfs/scratch_2/koen/nerf

conda install pytorch==1.13.0 torchvision pytorch-cuda=11.6 -c pytorch -c nvidia
pip install nerfstudio
pip install chardet







pip install torch torchvision functorch --extra-index-url https://download.pytorch.org/whl/cu117

pip install git+https://github.com/NVlabs/tiny-cuda-nn/#subdirectory=bindings/torch