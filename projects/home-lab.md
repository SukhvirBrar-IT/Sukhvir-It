# 🖥️ Home Lab Setup: Windows + Linux VMs with Segmented Networking

## 🔧 Objective
Build a safe, isolated environment to practice IT support tasks using virtual machines and basic networking.

## 🧱 Environment
- **Host OS**: Windows 10/11
- **Virtualization**: VirtualBox
- **VMs**:
  - Windows 11 Home Edition
  - Ubuntu 22.04 LTS VM
- **Networking**:
  - NAT for internet access
  - Host-Only for internal testing

## 🛠️ Steps Taken
1. Installed VirtualBox and created two VMs.
2. Installed Windows 11 and Ubuntu on separate VMs.
3. Configured NAT and Host-Only adapters for each VM.
4. Created standard user accounts and enabled RDP (Windows) and SSH (Ubuntu).
5. Took snapshots at key stages: baseline, post-update, post-software install.

## 📸 Screenshots
_Add screenshots here once uploaded:_
- VM settings
- IP configuration (`ipconfig` / `ip a`)
- RDP and SSH test results
- Snapshot list

## ✅ Results
- Verified network connectivity between VMs and host.
- Successfully accessed VMs remotely via RDP and SSH.
- Lab is ready for help desk simulations and troubleshooting practice.

## 🧠 Lessons Learned
- Importance of snapshots for rollback and testing.
- Host-only networks are great for safe internal testing.
- Practicing remote access setup builds real-world confidence.
