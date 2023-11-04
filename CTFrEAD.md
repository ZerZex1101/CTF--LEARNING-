# CTf TIPS And Commands 

##  `STEGANOGRAPHY`
```
steghide extract -sf stegosteg.jpg 
```
```
stegseek --seed [stegofile.jpg]
```
```
stegseek [stegofile.jpg] [wordlist.txt]
```

##   `Cryptography`
```
cyberchef   
crackstation.net
cryptii.com
d code .fr
factorDB - RSA CALCULATOR 
```

```
rar2john secure.rar > secure2.txt
john secure2.txt --wordlist=/usr/share/wordlists/rockyou.txt
```
```
HACKTOOLS EXTENSION - FIREFOX
```

###  ``dIRECTORY``
```
gobuster dir -e -u [ip] -w /usr/share/wordlists/dirb/common.txt
```

```
-w /usr/share/dirbuster/wordlists/directory-list-2.3-medium.txt 

```

```
/usr/share/seclists/Fuzzing/extensions-most-common.fuzz.txt
```



##  `smb`
```
smbclient //<IP>/anonymous
smbget -R smb://MACHINE_IP/anonymous
nmap -p 445 --script=smb-enum-shares.nse,smb-enum-users.nse MACHINE_IP

```
```
```
## Reverse Engineering 
```
ghidra```
``` binwalk
objdump ```
```
# ``IDA/RADAr``
```
```
```
r2 -d  filename
```
```
AAA - analayse 
```
```afl ```
```
```
```
pdf @main - view 
```
```
db - breakpoint
```
```
ood - proecess
```
```
dc - continue after breakpoint
```


