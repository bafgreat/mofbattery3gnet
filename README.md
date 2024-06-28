# Installation
Please read the installation instructions carefully. This is because the installation requires the installation of tensorflow which is proven to be quite tough depending on the platform.

It took me a while to figure out how to properly install tensorflow on macOS, windows and linux. Therefore to ensure that the installation is successful make to read read carefully the installation instructions

## Download
Begin by cloning the git repository to your environment.
```
git clone https://github.com/bafgreat/mofbattery3gnet.git
```
Once clone no cd to the repository
```
cd mofbattery3gnet
```
### NB
In the this directory there are two important configuration files. `tensorflow-apple-metal.yml` and `tensorflow-linux-window-metal.yml`. This configuration files are platform specific.
### i macOS installation
If your system is an apple device, create your Conda environment using `tensorflow-apple-metal.yml` configuration file as follows:
```
conda env create -f tensorflow-apple-metal.yml
```
###  ii linux system
If your system runs on linux,  please create your Conda environment using `tensorflow-linux-window-metal.yml` configuration file as follows:
```
conda env create -f tensorflow-linux-window-metal.yml
```
The above commands will create a new conda environment with tensorflow and most of the dependencies installed.

## NB
The above commands creates faster using mamba. Hence to use mamba start by installing mamba.
```
conda install mamba
```

Once mamba is installed, you could the proceed with either:
```
conda env create -f tensorflow-apple-metal.yml
```
or:
 ```
mamba env create -f tensorflow-linux-window-metal.yml
```
depending on your platform.



