# opsplash

 A command line tool unpack/repack oppo/realme/oneplus splash image

#
## Installation On Termux

```bash
apt update && apt upgrade -y
```

```bash
apt install git
```

```bash
git clone https://github.com/U89-sk/opsplash-android
```

```bash
cd opsplash-android
```

```bash
chmod +x opsplash
```

#
## - For More Information Read xda opsplash Page : <a href="https://forum.xda-developers.com/t/tool-splash-qcom-change-oppo-realme-oneplus-boot-splash-image.4498545">Link here</a>
#

## Usage
``` sh

Usage: opsplash [command] [-i] [-o]
                -i,--input              File input
                -o,--output             File/Dir output
        This is for oppo oneplus realme splash unpack/repack tool
        If you use this just take all risk by your self
        
Command support below:
        readinfo
        unpack
        repack

```

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

## Source & Credits
> https://github.com/affggh/opsplash
#
