# 🚀 API Chaining using Postman

This project demonstrates API chaining using Postman by passing dynamic data between requests.

## 🔗 Flow Implemented
1. Create User (POST)
2. Extract user ID from response
3. Pass ID to next request
4. Fetch User details (GET)

## 🛠 Tools Used
- Postman
- JavaScript (Postman scripting)

## 💡 Key Concepts
- Environment variables
- Dynamic data handling
- API chaining
- Response validation

## 📌 Sample Script
```javascript
var jsonData = pm.response.json();
pm.environment.set("id", jsonData.id);
