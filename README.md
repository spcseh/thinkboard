<h1 align="center">📝 MERN Stack Note Taking App ✨</h1>
<h3 align="center">Thinkboard</h3>

Highlights:

- 🧱 Full-Stack App Built with the MERN Stack (MongoDB, Express, React, Node)
- ✨ Create, Update, and Delete Notes with Title & Description
- 🛠️ Build and Test a Fully Functional REST API
- ⚙️ Rate Limiting with Upstash Redis — a Real-World Concept Explained Simply
- 🚀 Completely Responsive UI
- 🌐 Explore HTTP Methods, Status Codes & SQL vs NoSQL
- 📦 Deployment Guide Included — Add the Live App to Your Resume
- 📚 Designed for Absolute Beginners

---

## 🧪 .env Setup

### Backend (`/backend`)

```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## 🔧 Run the Backend

```
cd backend
npm install

npm install @upstash/ratelimit@2.0.6
npm install @upstash/redis@1.35.4
npm install cors@2.8.5

npm run dev
```

## 💻 Run the Frontend

```
cd frontend
npm install

npm install axios@1.9.0
npm install lucide-react@0.510.0
npm install react@19.1.0
npm install react-dom@19.1.0
npm install react-hot-toast@2.6.0
npm install react-router@7.9.3

npm run build
npm run dev
```
