# Nodepay Auto Farming
Feature:
- Quick installation with script
- Can running with proxy or Without proxy
- Can mining multi account
- Automatically remove inactive proxies

### Requirements
- Python3.10 or higher
- Pip3
- Python Environment

# Setup Tutorial
- Open [Nodepay](https://app.nodepay.ai/register?ref=ZUCBuJaIoBXLE6J) and login to dashboard
- Right click and **inspect**
- Select Console
```
localStorage.getItem('np_token')
```
⚠️ If you can't paste in the console, please type manually ```allow pasting```

# Installation
```
source <(curl -s https://raw.githubusercontent.com/ryzwan29/nodepay-multi-autoproxy/main/quick-installation.sh)
```

#### Run command
✅ If you're using a proxy
```
python3 run_proxy.py
```
⚠️ If you're not using a proxy
```
python3 noproxy.py
```

# Format Proxy
- http://ip:port
- http://user:pass@ip:port

