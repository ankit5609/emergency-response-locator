# Emergency Response Locator 🚑

A Java Spring Boot backend prototype that helps users find nearby hospitals, blood banks, and emergency services using location data.

## 🧩 Features
- RESTful APIs for hospital management and nearby search
- MySQL database integration for hospital data
- Google Maps API simulation for distance calculation
- Modular MVC architecture (Controller → Service → Repository)

## ⚙️ Tech Stack
**Backend:** Java, Spring Boot  
**Database:** MySQL  
**Tools:** Postman, Maven, IntelliJ IDEA  

## 🚀 API Endpoints (Example)
| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/hospitals | Fetch all hospitals |
| GET | /api/hospitals/nearby?lat=...&lng=... | Find nearby hospitals |
| POST | /api/hospitals | Add new hospital data |

## 📂 Project Structure
