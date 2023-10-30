# How to connect to ubc secure on linux

## Legacy crypto policies
On new linux distro's, you have to set the phase 2 crypto settings with:
```
update-crypto-policies --set LEGACY
```
On fedora linux, the command is:
```
sudo update-crypto-policies --set LEGACY
```
[documentation](https://unix.stackexchange.com/questions/674472/cant-connect-to-wpa2-peap-mschapv2-enterprise-wifi-network-without-a-certificat)

## Download manual certificate
1. Go to http://autoconnect.it.ubc.ca/
2. Press show all operating systems
3. Go to "other operating systems" and download the CA certificate

## Setup wifi
Security:         WPA2-Enterprise <br>
Authentication:   Protected EAP (PEAP) <br>
domain:           ubc.ca <br>
CA certificate:   (the one you downloaded) <br>
username:         (cwl username) <br>
password:         (cwl password) <br>
