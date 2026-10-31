# B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
Cybersecurity Lab setup

## 1. Project Overview

This project involved setting up a virtual cybersecurity lab environment using Oracle VirtualBox and Kali Linux, following the WK1-PM1 requirements provided by Networkwalks Academy.

The purpose of the lab is to establish a controlled virtual environment for future cybersecurity, ethical hacking, networking, and CTF practical exercises.

## 2. Tools Used

- Oracle VirtualBox – virtualization platform.
- 7-Zip – archive extraction utility.
- Kali Linux 2026.1 – cybersecurity testing machine.

## 3. VirtualBox Network Configuration

A custom NAT Network was created and configured according to the assignment requirements.

| Setting | Configuration |
|---|---|
| Network Name | NatNetwork |
| Network Type | NAT Network |
| IPv4 Network | 10.0.0.0/24 |
| Network Range | 10.0.0.2–10.0.0.99 |

## 4. Kali Linux Configuration

Kali Linux was successfully imported into VirtualBox and configured as the main virtual machine for cybersecurity exercises.

| Setting | Configuration |
|---|---|
| Operating System | Kali Linux 2026.1 |
| Network Adapter | NAT Network |
| Network Interface | eth0 |
| IPv4 Address | 10.0.0.2/24 |
| Default Gateway | 10.0.0.1 |

## 5. VirtualBox Integration Settings

The required integration features were configured:

- Shared Clipboard: Bidirectional.
- Drag and Drop: Bidirectional.
- Shared Folders: Enabled.
- Host shared folder: `/downloads`.

These features allow communication and file sharing between the host operating system and the Kali Linux virtual machine.

## 6. Internet Connectivity

Internet connectivity was configured and successfully tested from Kali Linux.

The following commands were used:

```bash
ping -c 4 1.1.1.1
ping -c 4 google.com
```

Both tests confirmed successful network connectivity and DNS resolution.

## 7. Conclusion

The WK1-PM1 lab setup was successfully completed according to the assignment requirements.

Oracle VirtualBox, the custom NAT Network, and Kali Linux were configured. Network connectivity, shared folders, clipboard integration, and drag-and-drop functionality were verified.

The virtual environment is now ready for future cybersecurity learning, ethical hacking practices.

---
