cd /etc/systemd/system

nano /etc/systemd/system/tunnel.service


----
[Unit]
Description=Reverse TLS Tunnel

[Service]
Type=idle
User=root
WorkingDirectory=/root/
ExecStart=/root/RTT --kharej --iran-ip:109.74.193.228 --iran-port:443 --toip:127.0.0.1 --toport:multiport --password:123 --sni:splus.ir
Restart=always

[Install]
WantedBy=multi-user.target

----

sudo systemctl daemon-reload &&
sudo systemctl enable tunnel.service &&
sudo systemctl start tunnel.service ;

sudo systemctl stop tunnel.service &&
sudo systemctl disable tunnel.service &&
sudo systemctl daemon-reload ;

sudo systemctl restart tunnel.service

systemctl status tunnel.service





pkill RTT


./RTT --iran --lport:23-65535 --sni:splus.ir --password:123


./RTT --kharej --iran-ip:109.74.193.228 --iran-port:443 --toip:127.0.0.1 --toport:multiport --password:123 --sni:splus.ir


----
[Unit]
Description=Reverse TLS Tunnel

[Service]
Type=idle
User=root
WorkingDirectory=/root
ExecStart=/root//RTT --iran --lport:23-65535 --sni:splus.ir --password:123
Restart=always

[Install]
WantedBy=multi-user.target

----
