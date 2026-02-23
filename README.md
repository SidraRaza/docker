# 🐳 Docker Beginner Guide

## 📌 Docker kya hai?

Docker aik **containerization tool** hai jo application ko uske code, libraries, aur dependencies ke sath pack karta hai.

Simple words mein:

👉 Docker = Box 📦  
👉 Application + Settings + Dependencies = Box ke andar  

Phir yeh application kisi bhi computer par same tarah run hoti hai.

---

## 🎂 Easy Example

- Recipe = Docker Image  
- Cake = Docker Container  

👉 Docker image = Blueprint / Template  
👉 Docker container = Running system  

---

## 🚀 Docker Image kya hoti hai?

Docker image aik **ready-made template** hoti hai jis se container banta hai.

- Image = Structure define karti hai  
- Container = Us structure ka running version hota hai  

---

## 🔧 Basic Docker Commands

### Docker version check karne ke liye
```bash
docker -v
 ```
###  Docker help dekhne ke liye
```bash
docker

```
### Image download karne ke liye
```bash
docker pull image_name
```

### Available images dekhne ke liye
```bash
docker images
```

### 🐳 Docker Test Karne ke Liye (Image Run Karna)

Docker mein kisi bhi image ko run karne ke liye yeh command use hoti hai:

```bash
docker run image_name
```

## 🖥️ Interactive Mode kya hota hai?

Interactive mode ka matlab hota hai **container ke andar live terminal use karna**.

Simple words mein:

👉 Aap container ke andar ja kar commands type kar sakte ho  
👉 Container ke sath live communication hota hai  

👉 Interactive mode use karne ke liye `-it` flag use hota hai:

```bash
docker run -it image_name
```

## 🚪 Container se Bahar Nikalna (Exit)

Agar aap container ke interactive mode mein hain aur bahar nikalna chahte hain, to yeh command use karen:

```bash
exit
```

## 📋 Running aur Closed Containers Dekhne ke Liye

Agar aap **sab containers (running + stopped)** dekhna chahte hain, to yeh command use karen:

```bash
docker ps -a
```

## 📋 Running Containers Dekhne ke Liye

Agar aap sirf **running containers** dekhna chahte hain, to yeh command use karen:

```bash
docker ps
```

## ▶️ Stopped Container Start Karne ke Liye

Agar aap stopped container ko dubara start karna chahte hain, to yeh command use karen:

```bash
docker start container_id
```

## ⏹️ Running Container Stop Karne ke Liye

Agar aap running container ko stop karna chahte hain, to yeh command use karen:

```bash
docker stop container_id
```

## 🗑️ Docker Image Delete Karne ke Liye

Agar aap Docker image remove karna chahte hain, to yeh command use karen:

```bash
docker rmi image_name
```

## 🗑️ Container Delete Karne ke Liye

Agar aap Docker container remove karna chahte hain, to yeh command use karen:

```bash
docker rm container_id
```

