# 📅 Day 5 Progress Report

## 🚀 Overview
Day 5 was mainly focused on project building and practical implementation.  
Less focus on DSA today, more on understanding real-world backend architecture and improving existing projects.

---

## 🧠 Data Structures & Algorithms
- Solved **1 DSA question**
- Focused on maintaining consistency rather than quantity
- Practiced logical thinking and step-by-step debugging

🔗 *[[Robot Return To Origin](https://leetcode.com/problems/robot-return-to-origin/description/?envType=daily-question&envId=2026-04-05)]*

---

## 🏗️ Project Work

### 🚖 Uber Microservices Clone
- Started building an Uber-like backend using Microservices Architecture
- Broke the system into smaller independent services
- Understood how services communicate with each other
- Used **RabbitMQ** for asynchronous communication between services
- Implemented **Long Polling** for handling real-time updates (like ride status)
- Learned the difference between:
  - Monolithic vs Microservices in practical implementation
- Focused on:
  - Scalability
  - Service separation
  - Clean backend structure
🔗 **Repository Link:** *[[Link](https://github.com/KomalGarg123-lab/Uber-Micro-services)]*

---

### 🏊 IITGN Swimming Pool Management System
- Improved the existing project by handling **image storage efficiently**

#### 🔄 Update:
- Replaced storing images in **SQL database** ❌  
  with using **ImageKit.io** ✅

#### 💡 Why this change?
- SQL databases are not optimized for storing images
- ImageKit provides:
  - Faster image delivery
  - Better optimization
  - CDN support
  - Reduced backend load

#### ⚙️ What I did:
- Integrated **ImageKit.io** with backend
- Uploaded images through API instead of storing in DB
- Stored only **image URLs** in database
- Improved overall system performance

🔗 **Repository Link:** *[[Link](https://github.com/KomalGarg123-lab/Swimming-Pool-Management-System/tree/main/swimmingpool)]*

---

## 📚 Key Learnings
- Practical understanding of Microservices Architecture
- Importance of separating services in large-scale systems
- Real-world approach to handling media storage
- Learned how third-party services like ImageKit improve performance

---

## 📌 Summary
- Solved 1 DSA question  
- Built foundation of Uber Microservices Clone* 
- Improved IITGN project with ImageKit integration  
- Focus was more on development and system design

---

## 🔥 Next Goals
- Continue building microservices (auth, ride, user service)
- Improve API communication between services
- Increase DSA practice consistency