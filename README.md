# env

```bash
adduser jitiandong
adduser jitiandong sudo
su - jitiandong
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
source ~/.bashrc
wget https://cdn.jsdelivr.net/gh/TildenJ/env/environment.yml
conda env update --prefix /home/jitiandong/miniconda3 --file environment.yml  --prune
pip install gpustat

sudo apt install git
git config --globa user.name TildenJ
git config --globa user.email j@itiandong.com
```
