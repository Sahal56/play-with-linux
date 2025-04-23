# **Play With Linux**

## **Description**
This projects aims to provides a person a list of toools & go around to complex installation, so that one can learn Linux with ease without having a dedicated Linux Machine.

| **Platform** | **Tools**      |
|--------------|----------------|
| Android      | [Termux](https://play.google.com/store/apps/details?id=com.termux)                   |
| iOS          | [iSH](https://ish.app/)                                                              |
| macOS        | [OrbStack](https://orbstack.dev/)                                                    |
| Windows      | [Ubunu-WSL](https://apps.microsoft.com/detail/9pdxgncfsczv)                          |

> NOTE : Your IP address can vary. Check with below given commands or Router's Home Page

## **Sreenshots**


<details>
<summary>Android</summary>

| **Device**  | **IP**            |
|-------------|-------------------|
| Android     | 192.168.1.32      |
| PC          | 192.168.1.27      |

| **Termux** |
|------------|
| ![Image](https://github.com/user-attachments/assets/faf50e1a-7553-4f3c-9113-15ae0fdbe838) |


| **Nano-Text Editor** |
|----------------------|
| ![Image](https://github.com/user-attachments/assets/a3d5bced-91be-4a43-b520-ac380f8d9797)
![Image](https://github.com/user-attachments/assets/086eed9b-1273-41d2-a39e-5895a244d377) |


| **SSH**  |   **PC/mac <-> android**   |
|------------------------|------|
| Generating Key Pair in Termux | ![Image](https://github.com/user-attachments/assets/2f1a991a-f0e5-447a-8cdc-a56219573190) |
| Send Public Key to PC/mac     | ![Image](https://github.com/user-attachments/assets/6bb29669-949c-4da4-8bfd-6b3fac234887) |
| SSH android-termux to mac     | ![Image](https://github.com/user-attachments/assets/497fdac2-a988-4a37-9f56-73c6d1f169a7) |
|SSH mac to android-termux      | <img width="424" alt="Image" src="https://github.com/user-attachments/assets/42bccfd0-9f43-4fa2-ab36-be7301093cea" /> |


**Commands:**
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

**Referrences:**
 - [ssh](https://wiki.termux.com/wiki/Remote_Access)

</details>
