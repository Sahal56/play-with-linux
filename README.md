# **Play With Linux**

## **Description**
This projects aims to provides a person a list of toools & go around to complex installation, so that one can learn Linux with ease without having a dedicated Linux Machine.

| **Platform** | **Tools**      |
|--------------|----------------|
| Android      | [Termux](https://play.google.com/store/apps/details?id=com.termux)                   |
| iOS          | [iSH](https://ish.app/)                                                              |
| macOS        | [OrbStack](https://orbstack.dev/)                                                    |
| Windows      | [Ubunu-WSL](https://apps.microsoft.com/detail/9pdxgncfsczv)                          |


## **Sreenshots**


<details>
<summary>Android</summary>

| Device  | IP           |
|---------|--------------|
| Android | 192.168.1.32 |
| PC | 192.168.1.27      |

| Termux |
|--|
|  |
| Nano-Text Editor |
| |
| SSH pc/mac <-> android |
| |
| |


Commands:
```sh
# Update System
apt update && apt upgrade -y

# Test Connectivity
ping -c 4 <ipaddr>

# Get IP
ifconfig | grep "inet"

# SSH install & Configure
pkg install openssh

# Termux uses porrt 8022
ssh-copy-id -p 8022 192.168.1.32
ssh -p 8022 sahal@192.168.1.32

```

Referrences:
 - [ssh](https://wiki.termux.com/wiki/Remote_Access)

</details>
