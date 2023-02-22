Find last modified files:
```bash
find -printf "%TY-%Tm-%Td %TT %p\n" | sort -n
```

Find last modified files with `ansible`:
```bash
find -printf "%TY-%Tm-%Td %TT %p\n" | sort -n | grep ansible
```

List network devices and IP address:
```bash
ip -br -c a
```
