## Termux-QDL
Flash Qualcomm CPU Based Mobile Phones Using Termux ```Without PC```
(This Tool Run Only in ```arm64``` architecture Termux Supported mobile) Root Required 

## installation :- 

```Install``` [termux](https://f-droid.org/repo/com.termux_1021.apk) & [termux api](https://f-droid.org/repo/com.termux.api_1000.apk) ```apk```
```console
pkg update && upgrade -y
```
```console
pkg install -y termux-api
```
```console
pkg install -y git
```
```console
pkg install -y libxml2
```
```console
pkg install -y sudo
```
```console
git clone https://github.com/Ishu43642/Termux-QDL.git
```
```console
cd Termux-QDL
```
```console
chmod +x qdl
```

## Run Tool
```console
./qdl
```


## Note :-
after Run this tool useg Details show in screen set your files location acording to useg details.

like this - ```sudo ./qdl --debug --storage emmc --include [flash file folder location] [prog_firhouse_xx.mbn file location] [rawprogram.xml file location] [patch.xml file location]```

Dont Add this ```[ ]``` on command line.

after Set commands Connect Terget Device to 9008 edl mode using Otg & Data cable.

## Video Guide ( Hindi) Don't forget to add sudo before commond ( because tool is updated did not work without root)

```How To Use Termux-QDL For Flashing Mobile```
https://youtu.be/qHwFG5pU7gk

```How To Bypass Mi account & Frp using Termux-QDL```
https://youtu.be/SV8wl06BTeg
