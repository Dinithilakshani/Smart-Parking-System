 Smart Parking Management System

> **A smarter way to park — powered by microservices, driven by innovation.**

![EurekaDashboard](https://github.com/user-attachments/assets/d85c6bce-418b-408c-a3b5-c21c158fe448)



---





## 🛠 How to Run the Project (Step-by-Step)

Follow this order for a smooth setup:

1. 🟢 **Start Eureka Server**  
   👉 [http://localhost:8761](http://localhost:8761)

2. ⚙️ **Start Config Server**  
   👉 [http://localhost:8888](http://localhost:8888)

3. 🚀 **Launch All Microservices**  
   Ensure each one registers in Eureka:
   - 👤 User Service → `http://localhost:8081`
   - 🚗 Vehicle Service → `http://localhost:8082`
   - 🅿 Parking Service → `http://localhost:8084`
   - 💳 Payment Service → `http://localhost:8085`

4. 🛣 **Run API Gateway**  
   👉 [http://localhost:8080](http://localhost:8080)

---

## 🧪 Testing APIs with Postman

📫 Easily test and explore all endpoints via API Gateway.

### 💼 Import the Collection

📥 [Download Postman Collection – smart-parking-management-system.postman_collection.json](smart-parking-management-system.postman_collection.json)

**How to use:**
1. Open Postman  
2. Click **Import**  
3. Upload the `.json` file  
4. ✅ Start testing!





