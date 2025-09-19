<<------------------ LINK: https://vaultmate.onrender.com/ -------------------------->>
1----📂 Vault Mate – Secure Cloud Document Storage
Vault Mate is a secure cloud storage platform designed for storing and managing sensitive documents like Aadhar, Passport, PAN card, Driving License, and more.
It provides a simple yet powerful way to upload, preview, and retrieve documents with authentication and encryption.

2----✨ Features
🔐 User Authentication – Signup/Login with JWT-based session handling.
🛡️ Secure Access – Protected routes using middleware token verification.
📑 Document Categories – Upload and manage Aadhar, Passport, PAN, Driving License, High School, Intermediate, and custom documents.
🖼️ Image Upload & Preview – Supports uploading and previewing documents in PNG/JPEG format.
🗄️ Database Integration – Store user metadata and documents in MongoDB.
⚡ Fast Backend – Powered by Node.js and Express.js.

3----🛠️ Tech Stack
--Backend--
Node.js – Runtime environment
Express.js – Backend framework
EJS – Template engine for rendering UI
Multer – File handling and image upload middleware
JWT (JSON Web Tokens) – Secure authentication
Cookie Parser – Manage session cookies
dotenv – Environment variable management
--Database--
MongoDB – User & image storage
Mongoose – MongoDB object modeling
Utilities & Services
Custom Save Image Service – Encodes and saves uploaded images in MongoDB
CryptoJS & bcrypt (future extension) – For encryption and password security

3----⚙️ Installation & Setup
# Clone the repo
git clone https://github.com/yourusername/VaultMate.git
cd VaultMate
# Install dependencies
npm install
# Setup environment
touch .env
# Add your MongoDB URI, JWT_SECRET, etc.
# Start server
npm start

4----🔮 Future Improvements
Mobile Application
End-to-end encryption for uploaded files
Role-based access control
Cloud deployment with AWS S3 for storage
CI/CD pipeline with Docker & Kubernetes
