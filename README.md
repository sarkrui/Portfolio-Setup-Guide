# WordPress Portfolio Setup Guide
This portfolio is to show how to deploy and maintain WordPress on a VPS. By following this guide, you will have:

* **Unlimited** websites hosting (depending on your VPS specs)
* An open-sourced GUI **Linux Control Panel** (named: *aaPanel*), consisting of File Manager, Linux Software Manager, Hosts Manager, Database Manager, Graphical System Status, etc
* **Schedulely backing up** websites and database to ftp, Google Drive, local disk, etc
* 

## Preparation 

### VPS Provider

* [Ultravps.eu (aff.)](https://www.ultravps.eu/?pdid=OA515F46535DO6331C64): where I deployed my [portfolio](https://pxing.design), 

### Domain

* [Namesilo](https://www.namesilo.com/register.php?rid=cdfeb54rn): the one I registered my domain: <u>pxing.design</u> and also the most afforable one among all domain providers
* [Namecheap](https://www.namecheap.com/logo-maker/app/new): offers student discount if you had a GitHub student pack
* [Godday](https://www.godaddy.com): the most well-known one



## Deployment

![image-20200225210514733](/Users/p.xing/Library/Application Support/typora-user-images/image-20200225210514733.png)

### aaPanel Installation

aaPanel is a simple but robust control panel for linux servers. It can manage the web server through a web-base GUI(Graphical User Interface). One of it most essential functionalities is to provide a one-click function hosting environment for users. If you already own a VPS, you can simply type the following command in your SSH console. 

*(N.B: Please also note that if you need to run aaPanel without any other LNMP/LAMP have been deployed. Keep your system pure!)*

#### Centos

```bash
yum install -y wget && wget -O install.sh http://www.aapanel.com/script/install_6.0_en.sh && bash install.sh
```

#### Ubuntu/Debian

```bash
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh
```

*(The Chinese version updates more frequently. Check [BaoTa](https://github.com/aaPanel/BaoTa) is you can read Chinese.)*

#### LNMP/LAMP

Once it is done, you will see a line of instruction saying: 

```
http://xxx.xxx.xxx.xxx:89898/xxxxxxx 
Login:xxxxx
Passcode: xxxx
```

Then, you will be able to login your aaPanel (BaoTa). After you sucessfully login, you will be consequently asked which Web engine to use, either **Ngnix** (LNMP) or **Apache** (LAMP). If your VPS has less than 1.5G of RAM, I would suggest to go with **Apache**, although **Ngnix** provides more cool features. 

### WordPress

Tbd

### Plugins

Tbd

### Theme

Tbd

### Custom CSS

```css

```





## Maintenance 

### Backup

#### Local backup

#### Remote backup



### Analtics 

#### Google Analytics

#### WP Statistics



### Acceleration

#### Memcached

#### WP Cache

#### Content Delivery Network

#### Object Storage Service (OSS)





 

