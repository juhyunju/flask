# raspberrypi 네트워크 설정

```
# sudo vi /etc/dhcpcd.conf
//아래 내용 추가
interface eth0
static ip_address=192.168.138.100
static routers=192.168.138.1
static domain_name_servers=192.168.138.1 8.8.8.8
static netmask=255.255.255.0
```
# flask 설치

```
# sudo apt-get install python3-flask
# mkdir wepapp
```
![led](https://user-images.githubusercontent.com/73158866/148722215-1d74f19f-0fc2-4571-9994-2d4045c31768.PNG)
