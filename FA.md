```sh
wget "https://raw.githubusercontent.com/radkesvat/FakeTlsTunnel/master/install.sh" -O install.sh && chmod +x install.sh && bash install.sh 
```


```sh
cd /etc/systemd/system
```

```sh
nano /etc/systemd/system/tunnel.service
```

```sh
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
```
----

```sh
sudo systemctl daemon-reload &&
sudo systemctl enable tunnel.service &&
sudo systemctl start tunnel.service ;
```

```sh
sudo systemctl stop tunnel.service &&
sudo systemctl disable tunnel.service &&
sudo systemctl daemon-reload ;
```
```sh
sudo systemctl restart tunnel.service
```

```sh
systemctl status tunnel.service
```




pkill RTT



```sh
./RTT --iran --lport:23-65535 --sni:splus.ir --password:123
```

```sh
./RTT --kharej --iran-ip:109.74.193.228 --iran-port:443 --toip:127.0.0.1 --toport:multiport --password:123 --sni:splus.ir
```

```sh
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
```
