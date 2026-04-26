# 1. Scan
```shell
sudo mdadm --assemble --scan
```

# 2. Mount
Before mount check with scan which sdc* exist:

```shell
mdadm --assemble --run /dev/md0 /dev/sdc1
```
