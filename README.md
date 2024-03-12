## Termux-QDL
Flash Qualcomm CPU Based Mobile Phones Using Termux ```Without PC```
(This Tool Run Only in ```arm64``` architecture Termux Supported mobile)

Tool Credit:- [Gautam Great](https://github.com/GautamGreat)

## installation :- 

```Install``` [termux](https://f-droid.org/repo/com.termux_118.apk) & [Termux-api](https://f-droid.org/repo/com.termux.api_51.apk) ```apk```
```console
yes | pkg update && upgrade
```
```console
pkg install termux-api
```
```console
pkg install git
```
```console
pkg install libxml2
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

like this - ```./qdl --debug --storage emmc --include "flash file folder location" "prog_firhouse_xx.mbn file location" "rawprogram.xml file location" "patch.xml file location"```

Remove this ```"``` from command line.

after Set commands Connect Terget Device to 9008 edl mode using Otg & Data cable.

## Video Guide ( Hindi)

```How To Use Termux-QDL For Flashing Mobile```
https://youtu.be/qHwFG5pU7gk

```How To Bypass Mi account & Frp using Termux-QDL```
https://youtu.be/SV8wl06BTeg
