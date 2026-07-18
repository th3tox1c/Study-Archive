*🚀 WINDOWS 11: WSL2 & KALI LINUX COMPLETE CONFIGURATION*
------------------------------------------------------------

------------------------------------------------------------


*🛠️ PHASE 1: ENABLE WINDOWS VIRTUALIZATION*
------------------------------------------------------------

* Action: Open PowerShell as Administrator.

* Run these commands to activate hypervisor hooks:

***Command 1:***
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```
***Command 2:***
```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```
### ***👉 [Must]: Reboot your PC now to apply hardware changes!***

------------------------------------------------------------

**📥 PHASE 2: SET WSL2 & INSTALL KALI LINUX**

------------------------------------------------------------

* Action: Open Command Prompt or PowerShell.

***Step 1: Install WSL***
```
wsl --install
```
***Step 2: Set WSL Version 2 as default***
```
wsl --set-default-version 2
```
***Step 3: Download and install official Kali image***
```
wsl --install -d kali-linux
```
👉 [NOTE]: Wait for download to hit 100%.

👉 Enter your new UNIX username and password when prompted.

------------------------------------------------------------

**⚡ PHASE 3: KALI CORE OPTIMIZATION & REPOS REFRESH**

------------------------------------------------------------

* Action: Inside the new Kali Linux Terminal.

* We must update metadata lists and upgrade default binaries.

***Command:***
```
sudo apt update && sudo apt upgrade -y
```
------------------------------------------------------------

**🧰 PHASE 4: DEPLOYING KALI CORE METAPACKAGES**

------------------------------------------------------------

* Explanation: Default WSL Kali is minimal (No hacking tools).

* Run this to pull the complete pentesting suite (Nmap, Hydra, etc.)

***Command:***
```
sudo apt install kali-linux-default -y
```

------------------------------------------------------------

**✅ SETUP COMPLETE!**



<div align="center">
Star the repo if this helped you! 🌟

<sub>⭐️ From [th3tox1c](https://github.com/th3tox1c)</sub>
</div>
