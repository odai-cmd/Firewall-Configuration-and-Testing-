# Firewall Configuration Lab

This project demonstrates hands-on firewall configuration and testing using UFW on Kali Linux.  
The goal is to understand how firewalls work in real-world environments by allowing necessary services, blocking insecure ports, testing connectivity, and monitoring firewall logs.

---

## 📌 Objectives

- Configure a firewall with secure default rules  
- Allow required network services  
- Block insecure or unnecessary ports  
- Test open and closed ports  
- Monitor and analyze firewall logs  

---

## 🛠 Tools & Technologies

- Kali Linux  
- UFW (Uncomplicated Firewall)  
- Netcat (nc)  
- Python temporary web server  
- systemd journal (journalctl)  

---

## 🔧 Firewall Configuration

Default rules:

- Deny all incoming traffic  
- Allow all outgoing traffic  

Ports configured:

- Port 80 (HTTP) → Allowed  
- Port 21 (FTP) → Blocked  

---

## 🧪 Testing

- A temporary Python web server was used to simulate a real web service on port 80  
- Netcat was used to verify open and blocked ports  
- Firewall logs were reviewed to confirm blocked traffic  

---

## 📊 Results

- Web traffic on port 80 was successfully allowed  
- FTP traffic on port 21 was blocked  
- Unauthorized incoming traffic was logged  
- System security was improved by reducing the attack surface  



## 📁 Project Files

- `Firewall_Report.md` — Detailed lab report and explanations  



## ✅ Conclusion

This lab provided practical experience with firewall configuration, testing, and monitoring.  
It demonstrated how firewalls are used in real-world systems to protect networks and control traffic.


## 🚀 Future Improvements

- Add advanced firewall rules  
- Implement IP-based filtering  
- Test using network scanning tools like nmap  
- Explore iptables and cloud firewalls  


## 👨‍💻 Author
Odai wahib
