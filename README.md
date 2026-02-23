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

### docker pull ubuntu
### Available images dekhne ke liye
```bash
docker images