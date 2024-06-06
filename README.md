# opsplash
A command line tool unpack/repack oppo/realme/oneplus splash image

# setup
```sh
apt update -y ; apt upgrade -y
```
#python3 make zlib-dev package
```sh
apt install make -y ; apt install zlib1g -y ; apt install python3 -y ; apt install pip -y && pip install setuptools ; pip install --upgrade setuptools
```
#cek my repository dependecies and then install

https://github.com/zetaxlinux/dependencies.git

## How to compile
### Main program
*** Need zlib-devel    
``` sh
make
```
### As python library
``` sh
python3 setup.py build
```
```sh
python3 setup.py install
```

## Usage
### Unpack oppo splash image    
``` sh
./opsplash unpack -i splash.img -o pic
```
    
### Repack oppo splash image
``` sh
./opsplash repack -i splash.img -o new-splash.img
```

### Only read image info
``` sh
./opsplash readinfo -i splash.img
```
