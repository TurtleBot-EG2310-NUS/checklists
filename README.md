# Checklists

## Boot up

### Ping all devices

#### Method 1
- Packages required
```bash
sudo apt install nmap
sudo apt install net-tools
```

- Run `ifconfig`
  **iOS Hostpot**

```bash
inet 172.20.10.3 netmask 0xfffffff0 broadcast 172.20.10.15
```

- Run 'nmap'
  
```bash
nmap -sn 172.20.10.0/24
```

#### Method 2

- Install angry ip scanner




