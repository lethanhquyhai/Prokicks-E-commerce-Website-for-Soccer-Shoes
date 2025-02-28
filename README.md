# ProKicks - Shoe Store Management System

## Introduction

ProKicks is a football shoe store management system that includes:
- **Frontend**: Angular application for user interface management.
- **Backend**: Node.js server handling API requests and database communication.
- **Database**: MongoDB for data storage.

---

## Installation Guide

### 1. **Install Required Tools**
- Install **Node.js** from [Node.js Official Website](https://nodejs.org/).
- Install **Angular CLI**:
  ```bash
  npm install -g @angular/cli
  ```
- Install **MongoDB Community Server** from [MongoDB Official Website](https://www.mongodb.com/try/download/community).

---

### 2. **Clone the Project**
Create a directory for the project and download the source code:
```bash
mkdir prokicks-project
cd prokicks-project
```

Clone the frontend repository:
```bash
git clone https://github.com/HieuCaoPhanTrung/Web_Business.git temp-repo
mv temp-repo/prokicks ./prokicks
```

Clone the backend repository:
```bash
mv temp-repo/my-server ./my-server
rm -rf temp-repo
```

After a successful clone, the project structure will be as follows:
```plaintext
prokicks-project/
├── prokicks/    # Frontend - Angular
├── my-server/   # Backend - Node.js
```

---

### 3. **Run the Frontend**
1. Navigate to the `prokicks` directory:
   ```bash
   cd prokicks
   ```
2. Install required dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   ng serve -o
   ```
4. The frontend will open in the browser at [http://localhost:4200](http://localhost:4200).

---

### 4. **Configure and Run the Backend**
1. **Install MongoDB and Create the Database**:
   - Open MongoDB Compass or terminal.
   - Create a database `prokicks_db` with the following collections:
     - **shoes**
     - **accessories**
     - **news**
   - Import relevant data into the collections from the `data` directory.

2. **Install Backend Dependencies**:
   - Navigate to the `my-server` directory:
     ```bash
     cd my-server
     ```
   - Install required dependencies:
     ```bash
     npm install
     ```

3. **Start the Backend Server**:
   ```bash
   npm start
   ```
4. The backend server will be running at [http://localhost:3000](http://localhost:3000).

---

### 5. **Usage**
- Open the frontend at [http://localhost:4200](http://localhost:4200).
- The backend system will run simultaneously at [http://localhost:3000](http://localhost:3000).
- Data is stored in the `prokicks_db` MongoDB database.

---

## Libraries Used

### **Frontend**
- Angular CLI
- Bootstrap (CSS Framework)

### **Backend**
- Express.js (Node.js Framework)
- Mongoose (MongoDB ORM)
- bcrypt.js (Password hashing)
- jsonwebtoken (JWT - User authentication)
- nodemailer (Email sending)

### **Database**
- MongoDB

---

## Authors
- Lê Thanh Quý Hải
- Cao Phan Trung Hiếu
- Nguyễn Văn Tài
- Trần Đức Lương
- Lương Chí Trung

---
