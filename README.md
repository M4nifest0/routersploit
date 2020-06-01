# RouterSploit - Exploitation Framework for Embedded Devices

[![Python 3.6](https://img.shields.io/badge/Python-3.6-yellow.svg)](http://www.python.org/download/)
[![Build Status](https://travis-ci.org/threat9/routersploit.svg?branch=master)](https://travis-ci.org/threat9/routersploit)

The RouterSploit Framework is an open-source exploitation framework dedicated to embedded devices.

[![asciicast](https://asciinema.org/a/180370.png)](https://asciinema.org/a/180370)

It consists of various modules that aids penetration testing operations:

* exploits - modules that take advantage of identified vulnerabilities
* creds - modules designed to test credentials against network services
* scanners - modules that check if a target is vulnerable to any exploit
* payloads - modules that are responsible for generating payloads for various architectures and injection points
* generic - modules that perform generic attacks 

# Installation

## Requirements

Required:
* future
* requests
* paramiko
* pysnmp
* pycrypto

Optional:
* bluepy - bluetooth low energy 

## Installation on Kali Linux

```
apt-get install python3-pip
git clone https://www.github.com/threat9/routersploit
cd routersploit
python3 -m pip install -r requirements.txt
python3 rsf.py
```

Bluetooth Low Energy support:
```
apt-get install libglib2.0-dev
python3 -m pip install bluepy
python3 rsf.py
```

## Installation on Ubuntu 18.04 & 17.10

```
sudo add-apt-repository universe
sudo apt-get install git python3-pip
git clone https://www.github.com/threat9/routersploit
cd routersploit
python3 -m pip install -r requirements.txt
python3 rsf.py
```

Bluetooth Low Energy support:
```
apt-get install libglib2.0-dev
python3 -m pip install bluepy
python3 rsf.py
```


## Installation on OSX

```
git clone https://www.github.com/threat9/routersploit
cd routersploit
sudo python3 -m pip install -r requirements.txt
python3 rsf.py
```

## Running on Docker

```
git clone https://www.github.com/threat9/routersploit
cd routersploit
docker build -t routersploit .
docker run -it --rm routersploit
```

# Update

Update RouterSploit Framework often. The project is under heavy development and new modules are shipped almost every day.

```
cd routersploit
git pull
```

# License

The RouterSploit Framework is under a BSD license.
Please see [LICENSE](LICENSE) for more details.


✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

⚠️ Read-First:

🔞The author of the does not encourage anyone to repeat this. Otherwise, you will be solely responsible. The was created for informational purposes. And for the fact that you caution you!🙏

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Description 👀

Title 📌 routersploit

💀 Made by ☠️👊 𝕿𝖍𝖎𝖘 𝕴𝖘 𝕿𝖍𝖊 𝓜4𝓷𝓲𝓯𝓮𝓼𝓽0 𝕿𝖊𝖆𝖒™💪🏴‍☠️

Author 🏴‍☠️ rainboy1 | erfan4lx | Vampire4lx

Aate ♾ 2020 May

Version 👁‍🗨 2.1.9

Usage 👌 cd routersploit

Channel  Combo List 👍  [![Telegram Chanel](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lxCombo)


✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

☠️👊𝓷𝓲𝓯𝓮𝓼𝓽4𝓷𝓲𝓯𝓮𝓼𝓽0 (MCS) Telegram Groups We are a team of  𝓑𝓵𝓪𝓬𝓴  𝓗𝓪𝓽  𝓗𝓪𝓬𝓴𝓮𝓻𝓼  because we know what is at stake. We prepare hackers by providing training and hacking tools. We are one of the few Black hat hacking teams that show you their skills.👁‍🗨💪

👇🏾👇🏾👇🏾👇🏾👇🏾

[![Join To Telegram Groups](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/M4nifest0)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Telegram Chat ID 📞 [![Telegram Chat](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lx)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

<p align="center">
  ✯ Follow Me On ♥️👇🏾👇🏾👇🏾
</p>
<p align="center">
  <a href="https://www.youtube.com/channel/UC73xXDVwfS8mE4ExtOg63sw/videos?view_as=subscriber">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIe0KA-4U2wilfj3CwcetOZYjaXr_C6bh5b9Xp3eDfeATwkhn82b70ELBt&s" width="40" height="40">
  </a>
  <a href="https://t.me/M4nifest0">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnOo5m2bMLsKVd9-ZjGf0xl0SAVqj9Fgxvu89_iu24qUcWQJ-X_1lvI5yOIA&s" width="40" height="40">
</p>

