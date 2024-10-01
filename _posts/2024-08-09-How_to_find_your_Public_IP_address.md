---
title: "How to find out what your Public IP address"
date: 09-08-2024
---

## Linux 

```bash
curl ipinfo.io/ip
curl -4 icanhazip.com
curl ipecho.net/plain
```

## Powershell

```powershell
$json = Invoke-WebRequest -Uri ipecho.net/plain
$json.Content
```
