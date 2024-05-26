# Create Application Nodejs

```bash
npm init
npm install express body-parser kafkajs
```

running

```bash
npm start
```

send message

```bash
curl -X POST http://localhost:8000/api/send -H "Content-Type: application/json" -d '{"message": "Nice to meet you..."}' 
```
