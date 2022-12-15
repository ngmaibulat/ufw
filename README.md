### Info

- Tool to automatically configure ufw rules
- Run via sudo

### JSON file with allowed ports

Create a file, with list of ports:

```json
[22, 443, 8080]
```

### Install

```bash
sudo npm i -g @aibulat/ctl-ufw
```

### Run

```
sudo ctl-ufw fw.json
```
