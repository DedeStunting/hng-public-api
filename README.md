# HNG12 Public API

This is a simple public API built for the HNG12 program. It provides basic information, including:  
- Your registered email address.  
- The current date and time in ISO 8601 format (UTC).  
- The GitHub URL of the project.  

---

## 🚀 Live API URL  
The API is live and publicly accessible at:  
**[hng-public-api](https://hng-public-api-8h4j.onrender.com)**  

---

## **🛠 Tech Stack**
- **Backend:** Node.js (Express)  
- **Hosting:** Render  
- **Version Control:** Git & GitHub  

---

## **📌 API Documentation**
### **Endpoint:**  
GET /

### **Response Format (200 OK)**  
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/DedeStunting/hng12-public-api"
}
```
---
## 🔄Example Usage

**Using cURL:**

curl -X GET https://hng12-public-api-8h4j.onrender.com

**Using Postman:**
Open Postman

Create a GET request to:
https://hng12-public-api-8h4j.onrender.com

Click Send and check the response.

---


## ⚙️ Setup Instructions
**Run Locally**
**Clone the repository:**
git clone https://github.com/DedeStunting/hng-public-api.git
cd hng-public-api

**Install dependencies:**
npm install

**Create a .env file and add:**

EMAIL=your-email@example.com

**Start the server:**
npm start

**Open in a browser or test with:**

curl -X GET http://localhost:3000

---

## 🌍 Deployments
This API is deployed on Render.

To deploy it yourself:
Push your code to a public GitHub repo.
Create a new Web Service on Render.
Connect your GitHub repository.

**Set the Start Command to:**
npm start

Set environment variables (EMAIL).

Deploy and get your public API URL.

📝 Author
**Name:** David Chiedu
**GitHub:** DedeStunting


