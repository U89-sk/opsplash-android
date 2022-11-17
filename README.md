# opsplash

 A command line tool unpack/repack oppo/realme/oneplus splash image

#
## Installation On Termux

```bash
termux-setup-storage
```

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
## - For More Information Read Opsplash xda : <a href="https://forum.xda-developers.com/t/tool-splash-qcom-change-oppo-realme-oneplus-boot-splash-image.4498545">Link here</a>
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

### Unpack splash image

How to copy paste Splash.img in Termux Directory
```bash
cp /sdcard/Download/splash.img splash.img
```
see your files
```sh
ls
```
``` sh
Unpack Command -
./opsplash unpack -i splash.img -o pic
```
How to replace bmp file in termux Directory

```bash
cp /sdcard/Download/boot.bmp pic/boot.bmp
```
    
### Repack splash image
Repack Command -
``` sh
./opsplash repack -i splash.img -o new-splash.img
```

How to Copy new-splash.img From Termux Directory

```bash
cp new-splash.img /sdcard/Download
```
### Only read image info
``` sh
./opsplash readinfo -i splash.img
```


### Extra Options

- JPG TO BMP CONVERTER : <a href="https://products.aspose.app/pdf/conversion/jpg-to-bmp">Link here</a>


## Source & Credits
> https://github.com/affggh/opsplash
#
