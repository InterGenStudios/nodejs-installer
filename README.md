![alt text](https://git.intergen.us/intergen/No-ReadMe/raw/master/InterGenStudios_600x338.jpg "InterGen Studios")

---

### Command line NodeJS installer for CentOS 6+ WHM/cPanel servers
---

Server root pass is required for use

#### To use:

```
mkdir -p /usr/local/src && cd /usr/local/src
wget https://raw.githubusercontent.com/InterGenStudios/nodejs-installer/master/instnjs
chmod +x instnjs
echo alias instnjs=\'/bin/bash /usr/local/src/instnjs\' >> ~/.bashrc
/bin/bash /usr/local/src/instnjs -h
source ~/.bashrc
```



#### To do list:
---
  1. Start cPanel Plugin GUI Development
  2. Everything else
