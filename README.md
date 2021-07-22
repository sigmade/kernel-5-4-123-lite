# Linux Kernel-5-4-123-sigmade (lite configuration) for Ubuntu Server 20.04 

Disabled:
 - WI-FI
 - Sound Card
 - AMD Processors
 - and others drivers

Only EXT4 filesystem

![image](https://user-images.githubusercontent.com/55326490/120222251-7544ee00-c261-11eb-83e2-5cc959ab144d.png)

`git clone https://github.com/sigmade/kernel-5-4-123-lite.git`

`mv * /usr/src/`

`dpkg -i linux-headers-5.4.123-sigmade_5.4.123-sigmade-1_amd64.deb 
 linux-image-5.4.123-sigmade_5.4.123-sigmade-1_amd64.deb
 linux-libc-dev_5.4.123-sigmade-1_amd64.deb`



