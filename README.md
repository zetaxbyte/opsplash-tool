# opsplash
A command line tool unpack/repack oppo/realme/oneplus splash image

# setup
```sh
apt update -y ; apt upgrade -y
```
#python3 make zlib-dev package
```sh
apt install make -y ; sudo apt install zlib1g -y ; pgk install python3 -y
```
#cek my repository dependecies and then install to

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
