# 📡 DCTCP (Data Center TCP)  

## 📖 Description  
This project implements **Data Center TCP (DCTCP)**, an enhanced congestion control protocol designed for data centers. DCTCP improves network performance by using **Explicit Congestion Notification (ECN)** to reduce latency, prevent queue buildup, and maintain high throughput.  

## 🛠 Features  
✅ **Alpha Estimation** – Dynamically estimates the fraction of marked packets.  
✅ **Congestion Window Adjustment** – Modifies the congestion window (CWND) based on congestion feedback.  
✅ **Explicit Congestion Notification (ECN)** – Signals congestion before packet loss occurs.  
✅ **Optimized for Data Centers** – Designed to handle high-throughput, low-latency environments.  

## 📊 DCTCP vs. TCP  
Traditional TCP struggles to efficiently handle network congestion in data centers, leading to queue buildup and high latency. DCTCP, introduced in **Windows Server 2012**, leverages **ECN** to estimate congestion and adjust the sending rate accordingly.  

### 🔍 Key Differences:  
| Feature         | TCP       | DCTCP      |  
|---------------|----------|------------|  
| Congestion Control | Packet Loss-based | ECN-based (proactive) |  
| Latency       | High      | Low         |  
| Throughput    | Variable  | Consistently High |  

## 📷 Visual Demonstration  
📌 The included graphs illustrate that **DCTCP achieves full throughput while occupying minimal buffer space**, unlike traditional TCP.  

## 🏗 Installation & Usage  
1. Clone the repository:  
   ```sh
   git clone https://github.com/MihaiSocea/DCTCP.git
   cd DCTCP
