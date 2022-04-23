# ovx
1. 2-3 with src
```
sudo vim /etc/apt/sources.list
```

2. 
```
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get build-dep openvpn -y
```

3. 
```bash
sudo curl -O https://raw.githubusercontent.com/tmdevgroup/ov/main/ov.sh
sudo chmod +x ov.sh
```
```sh
sudo ./ov.sh
```

4. 
```
systemctl restart openvpn@server.service
```

