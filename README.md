# aarch64-env

## qemu preparation

- install qemu
- qemu-img create <name> <size>

```bash
qemu-img create centos-8.4.img 40G
```

- download centos 8.4 iso

```bash
wget ...CentOS-8.4.2105-aarch64-dvd1.iso
```

- install os

```bash
bash start.sh
```

- start os & port map

```bash
bash start-1.sh

# in the qemu vm
dhcpclient
```

- ssh to vm

```bash
ssh -p 2222 root@127.0.0.1
```

## qemu param detail

TODO:

## pre install
- yum install cmake(ver: 3.18.2)