# B860H-HG680P-Armbian
User Default : root  
Password : 1234  

## Buat Bootable  
Extract  
Buat bootable dengan bootable maker ([Rufus](https://rufus.ie/) atau [balenaEtcher](https://www.balena.io/etcher/))  
Copy file dtb ke /dtb/amlogic
Download kernel di sini [ophub](https://github.com/ophub)
Copy folder amlogic ke dtb/amlogic


note : dtb sudah disesuaikan untuk RAM 2gb, untuk ram 1gb tidak perlu copy dtb

## Setting Armbian  
Setting WiFi, jam dll  
Login Armbian -> input command
```yaml
armbian-config
```

## Maximize penggunaan SDcard atau Flashdisk  
Perinatah ini bertujuan untuk menggunakan seluruh kapasitas yang tersedia sebagai ROOT  
Login Armbian -> input command
```yaml
armbian-tf
```
lalu pilih `Expand`

## Docker
Install Docker   
Login Armbian -> input command
```yaml
armbian-docker
```
  
  
Terimakasih untuk [ophub](https://github.com/ophub) yang telah menyediakan file iso armbian untuk amlogic s905x
