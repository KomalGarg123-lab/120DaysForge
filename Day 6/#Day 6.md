# 📅 Day 6 Progress

## ✅ DSA Practice
- Solved 2 Data Structures & Algorithms problems  
- Focused on:
  - Improving logical thinking  
  - Handling edge cases  
  - Writing cleaner and efficient code  

---

## ⚙️ Backend Learning

### 🐇 RabbitMQ (Deep Dive)
- Learned :contentReference[oaicite:0]{index=0} in detail  
- Understood its role in microservices architecture  
- Learned how services communicate asynchronously  
- Covered concepts:
  - Queues  
  - Producers & Consumers  
  - Message passing  

### ❓ Why RabbitMQ over Apache Kafka
- :contentReference[oaicite:1]{index=1} is suitable for:
  - Task-based systems (e.g., ride assignment)  
  - Reliable message delivery  

- :contentReference[oaicite:2]{index=2} is more suitable for:
  - High-volume data streaming  
  - Logs and analytics  

---

## 🔄 Polling Concepts

### 📌 Short Polling
- Client sends requests repeatedly to check for updates  
- Inefficient because:
  - Many requests return no new data  
  - Wastes server resources  

### 📌 Long Polling
- Server holds the request until:
  - Data is available, or  
  - Timeout occurs  
- More efficient than short polling  
- Reduces unnecessary API calls  

### 💡 Why Long Polling over Short Polling
- Fewer requests  
- Better performance  
- Lower server load  
- Near real-time response  

---

## ❓ Why NOT WebSockets or Server-Sent Events

### 🌐 WebSockets
- Provides real-time bidirectional communication  
- Not used because:
  - Adds complexity  
  - Requires persistent connection handling  
  - Not necessary for current project scale  

### 📡 Server-Sent Events (SSE)
- Server pushes updates to client (one-way)  
- Limitations:
  - Only one-way communication  
  - Less flexible  

---

## 🚖 Uber Backend Work
- Worked on Uber-like backend project  
- Implemented:
  - Long Polling for real-time ride updates  
- Gained understanding of:
  - Event-driven systems  
  - Backend responsiveness  
  - Asynchronous workflows  

---

## 🚀 Key Takeaways
- Learned why Long Polling is better than Short Polling  
- Understood trade-offs between:
  - Polling, WebSockets, and SSE  
- Clear understanding of:
  - RabbitMQ vs Kafka  
- Improved knowledge of real-time backend systems  
- Strengthened DSA problem-solving skills  