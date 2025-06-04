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
 
  ![image](https://github.com/user-attachments/assets/da4b8254-be72-43cd-8a9a-bfe7e2e1f0c0)


  ![image](https://github.com/user-attachments/assets/020f7098-ad26-4db8-b789-a9aeeb78382e)
  
  
  ![image](https://github.com/user-attachments/assets/00d2ea00-8964-42b9-a76d-3fc9e54d13c2)
  
  
  ![image](https://github.com/user-attachments/assets/fdf171ae-968b-49f5-a0f0-ef9aecf02a64)
  
  
  ![image](https://github.com/user-attachments/assets/8535ab86-237d-447e-8e08-bb418174bf7b)
   
## 🛠️ 3. Applied Filters

Used display filters to isolate specific protocols:

- `http` – HTTP traffic  
- `dns` – DNS queries and responses  
- `icmp` – ICMP echo (ping)  
- `tcp.port == 80` – Filter TCP traffic on port 80 

### 🔗 Example Filter Snapshots

![HTTP FILTER](https://github.com/user-attachments/assets/d217be24-0d8f-4eaa-91c1-d8a6b36ca812)


![HTTP FILTER](https://github.com/user-attachments/assets/09c6a1f5-6165-4b50-99d1-755e14fa4f52)


![DNS FILTER](https://github.com/user-attachments/assets/63433da8-6390-4884-abe5-402a26814dd0)


![SSH FILTER](https://github.com/user-attachments/assets/ec0599fd-37b5-4961-9dc9-913d50d23d2f)



## 📊 4. Packet Analysis (Wireshark)

### 🔍 Traffic Types Analyzed

- **HTTP Traffic**: Reviewed `GET`/`POST` requests and headers  
- **DNS Traffic**: Analyzed domain queries and responses   
- **TCP Traffic**: Inspected connection setup flags

  ### ✅ Observations & Learnings

| Protocol | What I Observed |
|----------|------------------|
| **HTTP** | Full request headers, plaintext URLs |
| **DNS**  | Hostname resolution with query/response |
| **TCP**  | 3-way handshake, port numbers, flags |

-I learned how packet structure changes across protocols  
-I understood how traffic can be filtered and investigated in real time  
-I noted how encrypted (HTTPS) vs. plaintext (HTTP) traffic differs  

---

### ⚠️ Security Insights

- Realized how much sensitive data can be exposed over unencrypted channels (e.g., HTTP)  

- Saw how attackers could potentially sniff credentials or session data on unsecured networks

- 🤝 Contributions
I am open to feedback, collaborations, and shared learning. If you're also pivoting into cybersecurity, let's connect and support each other.

📬 Contact
www.linkedin.com/in/abiodun-uche • abioduneniola24@gmail.com •












