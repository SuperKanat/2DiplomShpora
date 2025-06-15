# 2DiplomShpora

## Hostname
# hostnamectl hostname <>

## Timezone
# apt-get install tzdata
# timedatectl set-timezone ?/?

## ISP
## options
# /etc/net/ifaces/ens19/options
# dhcp >> static
## ipv4address
# 172.16.4.1/28
## iptables
# iptables -t nat -A POSTROUTING -j MASQUERADE -o ens18
## ip forvarding
# /etc/net/sysct.conf
# ipv4_forvard >> 1

## HQ-RTR or other machines lower
## ipv4route
# default via ??
## ipv4address
## options
# dhcp >> static 

## Add users
# useradd sshuser -u 1010, passwd sshuser
# usermod -aG wheel sshuser
# /etc/sudoers
# sshuser ALL=(ALL) NOPASSWD:ALL
