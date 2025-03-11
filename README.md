# Live Coding Interview - Django Money Transfer API

## 📝 Given:
- A **prebuilt Django project (`transactions_api`)** inside a **Docker container**.
- A **predefined PostgreSQL database**.
- The database is configured via **Docker Compose**.
- **Django is already installed with Django Rest Framework (DRF)**.
- Models and views **need to be implemented**.

🔗 Repository: [GitHub - webchainro/interview-python](https://github.com/webchainro/interview-python)

---

## 🎯 Task
Create an API endpoint for handling **money transfers between users**.

### **✅ Expected Success Response**
```json
{
  "message": "Transaction successful",
  "sender": {"id": 1, "username": "Alice", "balance": 800.00},
  "receiver": {"id": 2, "username": "Bob", "balance": 1200.00}
}
```

### **❌ Expected Failure Response**
```json
{
  "error": "Insufficient funds"
}
```
