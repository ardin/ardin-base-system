# Ardin Base System

## Description
Meta package with common packages and configuration.


## Files
* /etc/profile.d/ardin-base-system.sh - prompt and history configuration


## Packages
* epel-release (CentOS7 only)
* iotop
* sdparm
* pciutils
* strace
* ltrace
* ethstatus
* ethtool
* smartmontools
* hdparm
* vim
* vim-enhanced
* hddtemp
* wget
* sysstat
* telnet
* rpmconf
* mtr
* bind-utils
* ntpdate
* rsync
* nfs-utils
* socat
* iptraf
* iputils
* lsof
* openssh-clients
* bzip2
* links
* net-tools
* tcpdump
* mc
* whois
* perl-libwww-perl
* perl-LWP-Protocol-https
* git
* pwgen
* screen


## Installation

**Fedora 30**

* dnf copr enable ardin/ardin-tools -y
* dnf install ardin-base-system -y

**CentOS 7**

* yum install yum-plugin-copr -y
* yum copr enable ardin/ardin-tools -y
* yum install ardin-base-system -y

**Rocky 8**

* dnf install yum-plugin-copr -y
* dnf copr enable ardin/ardin-tools -y
* dnf install epel-release
* dnf install ardin-base-system -y


