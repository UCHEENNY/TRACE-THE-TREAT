# TRACE-THE-THREAT
# 📡 Lab: Network Traffic Capture and Analysis Using Wireshark

## 🗂️ Overview  
This lab focuses on capturing, inspecting, and analyzing real-time network traffic using **Wireshark**, a powerful packet analyzer. It demonstrates how to identify protocols, inspect packet headers, and filter traffic for security and performance insights.

---

## 🧠 Objectives

- Understand how to capture live network traffic
- Analyze packet-level data for common protocols. This project focuses on HTTP, DNS, ICMP,SSH)
- Apply display filters to isolate specific traffic types
- Interpret key packet fields (source/destination IPs, ports, flags, etc.)
- Identify abnormal patterns or potential security events

---

## 🛠️ Tools Used

- **Wireshark** 
- Ubuntu web browser (for generating HTTP/HTTPS traffic)
- Kali Command line Interface (for `ping`, `nslookup`, Brute force using hydra)
- Virtual Machine 

---

## 🔧 Steps Performed

### 1. **Started Wireshark and Selected Interface**
- Launched Wireshark
- Selected the active interface ('eth0`) for live capture

  ![image](https://github.com/user-attachments/assets/cfc2b3d0-d866-4ec1-94ea-1f32898adb9d)


### 2. **Captured Traffic**
- Started capture
- Opened websites to generate HTTP traffic
- Used terminal to:
  - Run `PING GOOGLE.COM`
  - Run `http commands
  - Performed SSH attack'
  - Run 'suspicious dns '

  ![image](https://github.com/user-attachments/assets/020f7098-ad26-4db8-b789-a9aeeb78382e)
  
  ![image](https://github.com/user-attachments/assets/00d2ea00-8964-42b9-a76d-3fc9e54d13c2)
  
  ![image](https://github.com/user-attachments/assets/fdf171ae-968b-49f5-a0f0-ef9aecf02a64)
  
  ![image](https://github.com/user-attachments/assets/8535ab86-237d-447e-8e08-bb418174bf7b)
   

### 3. **Applied Filters**
Used display filters to isolate specific protocols:
```wireshark
http                 # HTTP traffic
dns                  # DNS queries and responses
icmp                 # ICMP echo (ping)
tcp.port == 80       # Filter TCP traffic on port 80
ip.addr == x.x.x.x   # Focus on a specific host

![image](https://github.com/user-attachments/assets/0ccd26ac-9569-4f81-9271-f57f03c41ccf)
![image](https://github.com/user-attachments/assets/8535ab86-237d-447e-8e08-bb418174bf7b)







