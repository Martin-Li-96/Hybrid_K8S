#Raspberry Pi : *(Cgroup memory missing)*
```bash
#Ubuntu 20.04 or 22.04
sudo vi /etc/firmware/cmdline.txt

Append following command
cgroup_enable=cpuset
cgroup_enable=memory
cgroup_memory=1
```