# opsplash

 A command line tool unpack/repack oppo/realme/oneplus splash image

## Installation On Termux

```bash

apt update && apt upgrade -y

```

```bash

apt install git

```
git clone https://github.com/U89-sk/opsplash-android
```bash

cd opsplash-android

```
chmod +x opsplash-android
```bash


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




## Source & Cred
https://github.com/affggh/opsplash
