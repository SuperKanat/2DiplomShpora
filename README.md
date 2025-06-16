# 2DiplomShpora
https://github.com/damh66/demo2025?tab=readme-ov-file
![image](https://github.com/user-attachments/assets/8069b661-75e5-47da-9aa1-f51f0e02ea9e)
![image](https://github.com/user-attachments/assets/97a4a35f-0d39-474a-a6a2-b48e13c8981f)



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
