# Resolving Hyper-V for Windows Mission  
*Author: Tredarion Hampton • Last updated: 2025-06-14*

## Objective
Enable Hyper-V on Windows 10/11, resolve common conflicts, and verify Docker Desktop.

## Learning goals
- Turn on Hyper-V & WSL 2 features  
- Enable CPU virtualization in BIOS/UEFI  
- Diagnose memory-reservation and VM conflicts  

## Task list
1. **Pre-check**  
   ```powershell
   systeminfo | find "Hyper"
   ```

2. **Enable features** (PowerShell Admin)
   ```powershell
   dism /online /enable-feature /featurename:Microsoft-Hyper-V-All /all /norestart
   ```

3. **BIOS/UEFI** — enable Intel VT-x / AMD-V (photo proof)

4. **Post-check** — run `systeminfo` again

5. **Docker smoke-test** — `docker run hello-world` (screenshot)

## Troubleshooting

| Symptom                 | Cause          | Fix                                     |
|-------------------------|----------------|----------------------------------------|
| Hyper-V not available   | VT-x/AMD-V off | Enable in BIOS                          |
| Docker exit code 12     | Low memory     | Reduce VM RAM                           |
| VMware/VirtualBox fails | Hyper-V active | `bcdedit /set hypervisorlaunchtype off` |

## Resources
- [Enable Hyper-V (Microsoft)](https://learn.microsoft.com/windows-server/virtualization/hyper-v/get-started/enable-hyper-v)

> **Deliverable:** BEFORE & AFTER screenshots + 100-word summary.