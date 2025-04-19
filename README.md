# network-troubleshooting-project
 Simulated a network issue in a Windows 10 VM and resolved it using built-in tools.
# 🧪 Project 2 – Network Troubleshooting Simulation

**Goal:**  
Simulate a common IT support issue—no internet connection—and troubleshoot it using real-world tools.

---

## 🛠️ Tools Used
- Windows 10 Virtual Machine (VirtualBox)
- Network & Sharing Center
- Command Prompt (`ipconfig`, `ping`)

---

## 🔍 Tasks Completed
1. Disabled the Ethernet adapter in Network Connections to simulate a network failure.
2. Verified internet was down using:
   - Web browser (failed to load sites)
   - `ipconfig` (blank output confirmed no IP assigned)
   - `ping google.com` (failed to resolve host)
3. Re-enabled the adapter to restore connectivity.
4. Ran `ipconfig` and confirmed:
   - IPv4 address assigned
   - Gateway present
5. Successfully pinged Google to confirm internet was working again.

---

## ✅ Result
A realistic simulation of a basic connectivity issue that was diagnosed and resolved using manual network adapter management and command line tools.


---

👩🏽‍💻 *Project by Tayana 
