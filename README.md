# MOD Worker Panel

Modification with personal tweaks

## Features

- Optimized obfuscation (wont trigger CF AV and lite on CPU)
- Check after obfuscation for banned words (vless, bpb)
- Pick up to 10 IPs at random from cleanIPs (paste directly 300+ from scanner)
- Rate limiting support for vless
- Small changes here and there

## Installation

1. Install dependencies:
```bash
npm install wrangler --save-dev
```

2. Build the project:
```powershell
.\build.ps1
```

## ENV

env.ID is old UUID, env.PASS is old TROJAN_PASS, env.DATABASE must be the same as KV.NAME is old env.bpb

![image](https://github.com/user-attachments/assets/ba171ed5-c21d-4a89-b75e-927771c3e8eb)

## Credits

Fully based on [BPB Worker Panel](https://github.com/bia-pain-bache/BPB-Worker-Panel)

## Clean IPs

https://github.com/goingfine/WinCFScan

Example:`198.41.193.36 , 104.27.64.235 , 195.85.23.248 , 172.67.116.57 , 185.170.166.68 , 23.227.39.71 , 141.101.122.116 , 162.159.137.59 , 188.42.88.15 , 91.193.59.187 , 156.238.19.89 , 45.131.209.107 , 205.233.181.245 , 160.153.0.168 , 170.114.45.182 , 192.65.217.245 , 103.21.244.97 , 154.83.2.23 , 147.185.161.168 , 168.100.6.44 , 199.181.197.37 , 89.116.250.172`

You can use https://github.com/vadash/CFScanParser to parse json
