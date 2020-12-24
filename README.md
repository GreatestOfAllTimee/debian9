Informasi :
# Update Module :
apt update && apt upgrade -y && update-grub

# Instalation Debian 9 :
apt update && apt upgrade -y && wget https://raw.githubusercontent.com/sshsedang/debian9/main/sshsedang.sh && chmod +x sshsedang.sh && ./sshsedang.sh

# Feature :
OpenSSH : 22, 143, 2507
Dropbear : 111, 222, 333
SSL : 444 (openvpn SSL) 
OpenVPN : 443 (TCP) 445 (UDP)
Squid3 : 80, 3128, 8080 (limit to IP SSH)
Config OpenVPN: http://myip:81/sshsedang.zip
badvpn udpgw : badvpn-udpgw port 7200
nginx : 81

# Note :
Setelah selesai install ssh, Harap restart stunnel4 & squid !!!

# Dibuat Oleh :
Ipang NetNot : 
https://github.com/janda09
