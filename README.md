# ubuntu-termux
Install run a mini distro Ubuntu on Termux

<hr/>

### installing the lib on termux:

```sh
~$ pkg update # update packages

~$ pkg i python3 -y # installing the python3

~$ pip3 install ubuntu-termux
```

###  installing the Ubuntu run:

```sh
~$ installubuntu # installing the Ubuntu
```

#### return ...
```sh
root@localhost:~#
```


### init ubuntu 
```sh
~$ ubuntu
root@localhost:~#
```

#### showing that it is ubuntu arm on termux
```sh
root@localhost:~# cat /etc/os-release
PRETTY_NAME="Ubuntu 22.04.2 LTS"
NAME="Ubuntu"
VERSION_ID="22.04"
VERSION="22.04.2 LTS (Jammy Jellyfish)"
VERSION_CODENAME=jammy
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=jammy
```
