
Download
```shell
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```  

Installation
```shell
bash Miniconda3-latest-Linux-x86_64.sh
```

export path conda
```shell
export PATH=~/miniconda3/bin:$PATH
```

reboot (required)
```shell
sudo reboot
```

Check you conda version
```shell
conda -V
```

set auto activate base environment (not required)
```shell
conda config --set auto_activate_base true
```