## Linux Snippets
Commonly used Linux commands for personal use. **Only for Debian/Ubuntu.**

### Install Speedtest
```bash
curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | bash && apt-get install speedtest -y
```

### Install Docker
```bash
curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
```

### Install Hy2
```bash
bash <(curl -Ls https://qwq.mx/hy2)
```

### Install WARP
```bash
bash <(curl -fsSL git.io/warp.sh)
```

### YABS CPU 
```bash
# Geekbench 5
curl -sL yabs.sh | bash -s -- -f -i -5
```

```bash
# Geekbench 6
curl -sL yabs.sh | bash -s -- -f -i -6
```

### Netflix Unlock by sjlleo
```bash
wget -O nf https://github.com/sjlleo/netflix-verify/releases/download/v3.1.0/nf_linux_amd64 && chmod +x nf && ./nf
```

### Install Nexttrace
```bash
bash <(curl -Ls https://raw.githubusercontent.com/sjlleo/nexttrace/main/nt_install.sh)
```

### Apply SSL Cert
```bash
bash <(curl -Ls https://cdn.jsdelivr.net/gh/missuo/AutoApplyCert/apply.sh)
```

### Media Unlock
```bash
bash <(curl -L -s check.unlock.media)
```
### Netflix Simple
```bash
bash <(curl -sSL "https://cdn.jsdelivr.net/gh/missuo/SimpleNetflix/nf.sh")
```

### Bench
```bash
wget -qO- bench.sh | bash
```

### LemonBench
```bash
curl -fsSL http://ilemonra.in/LemonBenchIntl | bash -s fast
```

### BBR
```bash
wget -N --no-check-certificate "https://github.000060000.xyz/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
```

### aaPanel Remove AD
```bash
wget -O /www/server/panel/BTPanel/static/js/index.js https://raw.githubusercontent.com/missuo/aaPanelEnhanced/main/index.js
```

### Install aaPanel
```bash
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && bash install.sh forum
```

### Modify Hostname
```bash
hostnamectl set-hostname missuo.me
```

### Install XanMod Kernel
```bash
apt update -y && apt install gnupg2 -y
wget -qO - https://dl.xanmod.org/archive.key | gpg --dearmor -o /usr/share/keyrings/xanmod-archive-keyring.gpg
echo 'deb [signed-by=/usr/share/keyrings/xanmod-archive-keyring.gpg] http://deb.xanmod.org releases main' | tee /etc/apt/sources.list.d/xanmod-release.list
apt update && apt install linux-xanmod-x64v3
```

