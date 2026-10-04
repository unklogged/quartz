User ID and Groups
```bash
id
whoami
groups
```

OS and Kernel
```bash
uname -a
cat /etc/os-release
```

List all listening TCP/UDP ports and associated processes
```bash
ss -tulnp
```

SUID + SGID binaries with permissions
```bash
find / -type f \( -perm -4000 -o -perm -2000 \) -exec ls -al {} \; 2>/dev/null
```

Check CUPS Version
```bash
cups-config --version
```