# 📌 Cloud-Based Smart Attendance System  
### ✅ QR Code Based | ✅ Geo-Location Verification | ✅ Firebase Cloud Functions | ✅ Firestore | ✅ Fully Responsive

This project is a **cloud-powered attendance automation system** designed for colleges and institutions.  
Teachers can generate a **QR-based attendance session**, students scan it using their phones, and the system automatically verifies their **real-time location** to prevent proxies.

---

## 🚀 Features

### ✅ **Teacher Panel**
- Generate secure QR-based attendance sessions  
- Auto-embed geo-location (lat/lon) of classroom  
- Set custom verification radius (e.g., 50–100 meters)  
- Live session token generation  
- One-click link to Dashboard & Scanner  

### ✅ **Student Scanner**
- Students enter their name + enrollment once  
- Scan QR → location auto-captured → attendance submitted  
- Prevents proxy:  
  - ✅ Inside radius = **Verified Present**  
  - ❌ Outside radius = **Unverified Attempt (Proxy)**  

### ✅ **Admin Dashboard**
- Full attendance table (ID, Name, Course, Status, Timestamp)  
- Real-time updates via Firestore  
- Present vs. Absent pie-chart  
- Export-ready structured data  

### ✅ **Backend (Cloud Functions)**
- REST APIs: `/createSession`, `/checkin`, `/getAttendanceWithRoster`  
- Geo-verification using **Haversine Formula**  
- Secure serverless deployment (scales automatically)

### ✅ **Database (Firestore)**
- Collections:
  - `students/`
  - `sessions/`
  - `attendance/`
- Optimized for fast querying & analytics

---

## 🏗️ System Architecture

<img width="541" height="415" alt="image" src="https://github.com/user-attachments/assets/61151eee-c4cd-4b1e-ae31-b2ffab6b1b79" />

🌍 Live Project:https://cc-lab-project-attendance.web.app/

👨‍💻 Author

Malay Singh Bisht
Department of Information Technology
SGSITS, Indore
📧 malaysinghbisht@gmail.com


