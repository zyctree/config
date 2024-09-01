```bash
iwctl

sudo systemctl enable systemd-resolved
sudo systemctl start systemd-resolved
```


/etc/systemd/resolved.conf.d/dns_servers.conf

```conf
[Resolve]
DNS=8.8.8.8
Domains=~.
```
iwd

/etc/iwd/main.conf
```conf
[General]
EnableNetworkConfiguration=true

[Network]
NameResolvingService=systemd
```
