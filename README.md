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

sudo apt install -y git tmux
git config --globa user.name TildenJ
git config --globa user.email j@itiandong.com
```


```bash
adduser jitiandong
passwd jitiandong
usermod -G wheel jitiandong

su - jitiandong
sudo yum install wget
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
source ~/.bashrc
wget https://cdn.jsdelivr.net/gh/TildenJ/env/environment.yml
conda env update --prefix /home/jitiandong/miniconda3 --file environment.yml  --prune
pip install gpustat

sudo apt install -y git tmux
git config --globa user.name TildenJ
git config --globa user.email j@itiandong.com
```

```bash
sudo userdel -r jitiandong

# centos
yum install make automake gcc gcc-c++ kernel-devel

#ubuntu
apt install build-essential

conda env create -f environment.yml
```
