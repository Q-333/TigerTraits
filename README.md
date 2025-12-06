# TigerTraits

TigerTraits is a full-stack web application consisting of:
- **Node/Express API** (`node-server`)
- **Angular frontend**
- **MongoDB database** (via Docker)

---

## Prerequisites
Make sure you have the following installed:
- **Node.js** (v18+ recommended)
- **npm**
- **Angular CLI** → `npm install -g @angular/cli`
- **Docker** (used to run MongoDB)

---

## Getting Started (Local Development)

### 1. Clone the Repository
Run the following commands:

git clone https://github.com/Q-333/TigerTraits.git
cd TigerTraits

---

### 2. Start MongoDB (Docker)
Start the MongoDB container:

docker run -d --name mongo -p 27017:27017 mongo:6

MongoDB will now be available at:

mongodb://localhost:27017

---

### 3. Start the API Server
Navigate to the backend and start the server:

cd node-server
npm install
npm start

The API will be running at:

http://localhost:3000

---

### 4. Start the Angular Frontend
Return to the root folder and start the Angular app:

cd ..
npm install
ng serve

The frontend will be available at:

http://localhost:4200