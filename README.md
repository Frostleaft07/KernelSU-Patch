# KernelSU-Patch
add kernelsu > kernel non GKI

# How?
```
wget https://raw.githubusercontent.com/Frostleaft07/KernelSU-Patch/main/KSU.patch
```
and
```
patch -p1 < KSU.patch
```
then 
```
rm -rf KernelSU
```
and add KernelSU to your kernel source tree:
```
curl -LSs "https://raw.githubusercontent.com/tiann/KernelSU/main/kernel/setup.sh" | bash -
```
Done :)

![ex](https://raw.githubusercontent.com/Frostleaft07/KernelSU-Patch/main/Cuplikan%20Layar_2024-02-06_11-00-48.png "ex")

