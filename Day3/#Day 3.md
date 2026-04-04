# 📅 Day 3 Progress Report

## ✅ What I Did Today

### 🔹 DSA Practice

* Solved 5 questions(3 Of Array and 2 of BS) of Data Structures and Algorithms.
* Focused on improving problem-solving skills and logic building.
* Practiced thinking from brute force → optimized approach.

📌 **Questions Solved:**

* [ ] 3Sum ([add link](https://leetcode.com/problems/3sum/description/))
* [ ] 3Sum Closest ([add link](https://leetcode.com/problems/3sum-closest/description/))
* [ ] 4Sum ([add link](https://leetcode.com/problems/4sum/description/))
* [ ] BS on real answers ([add link](https://codeforces.com/edu/course/2/lesson/6/2/practice/contest/283932/problem/A))
* [ ] BS on real answers ([add link](https://codeforces.com/edu/course/2/lesson/6/2/practice/contest/283932/problem/B))


---

### 🔹 DevOps Learning

* Learned the basics of DevOps.

#### 💡 What is DevOps?

DevOps is a practice that combines:

* **Development (Dev)** + **Operations (Ops)**

#### 🚀 Why DevOps is used:

* Faster development and deployment
* Better collaboration between teams
* Continuous integration and delivery (CI/CD)

---

### 🔹 Docker Learning 🐳

#### 💡 What is Docker?

Docker is a tool used to run applications inside containers.

#### 🤔 Why we use Docker?

* To avoid "works on my machine" problem
* Same code runs on all systems (Windows, Linux, etc.)
* No need to install dependencies manually every time

#### 📦 What is a Container?

A container includes:

* Application code
* All required dependencies
* Environment setup

👉 So the app runs exactly the same everywhere.

---

### 🔧 How Docker Works (Basic Flow)

#### 1. Dockerfile

* A file that contains instructions to build your app

```
FROM node:18
WORKDIR /app
COPY . .
RUN npm install
CMD ["npm", "start"]
```

#### 2. Build Image

```
docker build -t my-app .
```

#### 3. Run Container

```
docker run -p 3000:3000 my-app
```

---

### 📌 Important Concepts

* **Image** → Blueprint of application
* **Container** → Running instance
* **Dockerfile** → Instructions to build image
* **Docker Hub** → Storage for images

---

### ⚠️ Issue Faced

* Docker is not working on my laptop

👉 Will fix this in upcoming days.

---

## 📌 Reflection

* Good balance between DSA practice and learning new technology
* Need to fix Docker to move from theory → practical
* Consistency maintained ✅

---

---

✨ *Consistency is the key. Keep going!*
