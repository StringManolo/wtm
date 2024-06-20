# wtm
WebTextMiner extracts text from webs to create wordlists usefull for brute-force attacks

### Download

```bash
git clone https://github.com/stringmanolo/wtm
cd wtm
```

### Install

##### In Linux and Proot-Distro
```bash
chmod +775 wtm.sh
mv wtm.sh /bin/wtm
```

##### In Termux
```bash
mv wtm.sh /data/data/com.termux/files/usr/bin/wtm
```

### Usage
```bash
wtm -u url -f filename -d depth_level
```


### Example
```bash
wtm -u https://example.com -f passwords.txt -d 2
```

