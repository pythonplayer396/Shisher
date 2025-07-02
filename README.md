<!-- Shisher -->

<p align="center">
  <img src=".github/misc/logo.png">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.3.5-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/pythonplayer396/shisher?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/pythonplayer396/shisher?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/pythonplayer396/shisher?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/pythonplayer396/shisher?color=teal&style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-darkwall-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Discord-darkwall%231234-blueviolet?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-darkgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-lightblue?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
</p>

<p align="center"><b>A beginner-friendly, automated phishing tool with 30+ templates.</b></p>

##

<h3><p align="center">Disclaimer</p></h3>

<i>Any actions and or activities related to <b>Shisher</b> are solely your responsibility. The misuse of this toolkit can result in <b>criminal charges</b> brought against the persons in question. <b>The contributors will not be held responsible</b> in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

<b>This toolkit contains materials that can be potentially damaging or dangerous for social media</b>. Refer to the laws in your province/country before accessing, using, or in any other way utilizing this in a wrong way.

<b>This Tool is made for educational purposes only</b>. Do not attempt to violate the law with anything contained here. <b>If this is your intention, then Get the hell out of here</b>!

It only demonstrates "how phishing works". <b>You shall not misuse the information to gain unauthorized access to someone's social media</b>. However, you may try out this at your own risk.</i>

##

### Features

- Latest and updated login pages
- Beginner-friendly
- Multiple tunneling options:
  - Localhost
  - Cloudflared
  - LocalXpose
- Mask URL support
- Docker support

##

### Installation

- Clone this repository:
  ```
  git clone --depth=1 https://github.com/pythonplayer396/shisher.git
  ```

- Go to the cloned directory and run `shisher.sh`:
  ```
  cd shisher
  bash shisher.sh
  ```

- On first launch, it will install the dependencies. That's it—***Shisher*** is installed.

##

### Installation (Termux)
You can easily install Shisher in Termux by using tur-repo:
```
pkg install tur-repo
pkg install shisher
shisher
```

### Note:
***Termux discourages hacking.*** Never discuss anything related to *shisher* in any Termux discussion groups. For more, check the [wiki](https://wiki.termux.com/wiki/Hacking).

##

<p align="left">
  <a href="https://shell.cloud.google.com/cloudshell/open?cloudshell_git_repo=https://github.com/pythonplayer396/shisher.git&tutorial=README.md" target="_blank"><img src="https://gstatic.com/cloudssh/images/open-btn.svg"></a>
</p>

##

### Installation via ".deb" file

- Download `.deb` files from the [**Latest Release**](https://github.com/pythonplayer396/shisher/releases/latest)
- If you are using ***Termux*** then download the `*_termux.deb`

- Install the `.deb` file by executing:
  ```
  apt install <your path to deb file>
  ```
  Or
  ```
  dpkg -i <your path to deb file>
  apt install -f
  ```

##

### Run on Docker

- Docker Image Mirror:
  - **DockerHub**:
    ```
    docker pull pythonplayer396/shisher
    ```
  - **GHCR**:
    ```
    docker pull ghcr.io/pythonplayer396/shisher:latest
    ```

- By using the wrapper script [**run-docker.sh**](https://raw.githubusercontent.com/pythonplayer396/shisher/master/run-docker.sh):

  ```
  curl -LO https://raw.githubusercontent.com/pythonplayer396/shisher/master/run-docker.sh
  bash run-docker.sh
  ```
- Temporary Container:

  ```
  docker run --rm -ti pythonplayer396/shisher
  ```
  - Remember to mount the `auth` directory.

##

<details>
  <summary><h3>Dependencies</h3></summary>

<b>Shisher</b> requires the following programs to run properly:
- `git`
- `curl`
- `php`

> All dependencies will be installed automatically when you run **Shisher** for the first time.
</details>

<details>
  <summary><h3>Tested on</h3></summary>

- **Ubuntu**
- **Debian**
- **Arch**
- **Manjaro**
- **Fedora**
- **Termux**
</details>

##

<h3 align="center"><i>:: Workflow ::</i></h3>
<p align="center">
<img src=".github/misc/workflow.gif"/>
</p>

##

### Find Me on
<p align="center">
  <a href="https://github.com/pythonplayer396" target="_blank"><img src="https://img.shields.io/badge/Github-blue?style=for-the-badge&logo=github"></a>
</p>

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" width="120" alt="phisher logo"/>
</p>

<p align="center" style="font-size:1.5em; font-weight:bold; color:#ff6600;">
  <b>shisher</b>
</p>
<p align="center" style="font-size:1.1em; color:#333;">
  <em>made by <b>darkwall</b></em><br>
  <a href="https://discord.com/users/1238914120179515402">discord - darkwall</a>
</p>
