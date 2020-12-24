Informasi :
# Update Module :
apt update && apt upgrade -y && update-grub

# Instalation Debian 9 :
apt update && apt upgrade -y && wget https://raw.githubusercontent.com/sshsedang/debian9/main/sshsedang.sh && chmod +x sshsedang.sh && ./sshsedang.sh

# Feature :
<br>OpenSSH : 22, 143, 2507
<br>Dropbear : 111, 222, 333
<br>SSL : 444 (openvpn SSL) 
<br>OpenVPN : 443 (TCP) 445 (UDP)
<br>Squid3 : 80, 3128, 8080 (limit to IP SSH)
<br>Config OpenVPN: http://myip:81/sshsedang.zip
<br>badvpn : badvpn-udpgw port 7200
<br>nginx : 81

# Note :
<br>Setelah selesai install ssh, Harap restart stunnel4 & squid !!!

# Dibuat Oleh :
Ipang NetNot : 
https://github.com/janda09
