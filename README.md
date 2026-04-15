# SDN Host Discovery using Mininet

## 📌 Problem Statement

To design and implement a Host Discovery Service in a Software Defined Network (SDN) that dynamically detects hosts and maintains their details.

---

## 🛠 Tools & Technologies

* Mininet (Network Emulator)
* Ubuntu 22.04
* Open vSwitch
* SDN Concepts

---

## ⚙️ Setup & Execution

### 1. Install Mininet

sudo apt install mininet -y

### 2. Run Mininet

sudo mn

### 3. Test Connectivity

pingall

---

## 🔍 Host Discovery Implementation

Host discovery is performed using Mininet commands:

* `nodes` → Lists all hosts and switches
* `net` → Shows network topology
* `dump` → Displays host details (IP, MAC, interfaces)

---

## 📊 Output

* Successful connectivity between hosts (0% packet loss)
* Dynamic detection of hosts and their details

---
## 💻 Conceptual Logic (Pseudo Code)

1. Start Mininet network
2. Create hosts and switches
3. Establish connections
4. Send packets using ping
5. Capture host details using dump
6. Display IP, MAC, and connectivity

## 📸 Proof of Execution

### ✅ Ping Test


### ✅ Host Discovery Output


---

## 🧠 Key Concepts Used

* Software Defined Networking (SDN)
* Network Topology Simulation
* Virtual Hosts & Switches
* Host Discovery Mechanism

---



## ✅ Conclusion

This project successfully demonstrates host discovery in an SDN environment using Mininet. The system dynamically identifies hosts and provides their details such as IP address, MAC address, and connectivity.

---
## 🧪 Commands Used

sudo mn  
pingall  
nodes  
net  
dump  

## 👩‍💻 Author

Sreehitha Karanam

ScreenShot1:Pingall
<img width="940" height="586" alt="image" src="https://github.com/user-attachments/assets/89f8080a-d790-4087-b1ca-599b33dce9de" />
ScreenShot2 :dump
<img width="940" height="583" alt="image" src="https://github.com/user-attachments/assets/6a2e938d-e522-4ee6-9791-a8c0144032b7" />

