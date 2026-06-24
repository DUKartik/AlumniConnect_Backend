<h1 align="center">🎓 Alumni Connect OS</h1>

<p align="center">
  AI-Powered Alumni–Student Networking Platform for SIH 2025
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Backend-green" />
  <img src="https://img.shields.io/badge/React-Frontend-blue" />
  <img src="https://img.shields.io/badge/MongoDB-Database-brightgreen" />
  <img src="https://img.shields.io/badge/Gemini-AI-orange" />
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-black" />
  <img src="https://img.shields.io/badge/Cloudinary-Media-blueviolet" />
</p>

<hr>

<h2>🚀 Overview</h2>

<p>
Alumni Connect OS is a full-stack alumni and student engagement platform designed to strengthen networking, mentorship, communication, and professional growth within educational institutions.
</p>

<p>
The platform provides secure role-based access, alumni verification workflows, AI-powered event creation, real-time chat, profile evaluation, and face-recognition-based user discovery.
</p>

<hr>

<h2>🏗️ Tech Stack</h2>

<h3>Frontend</h3>

<ul>
<li>React 19</li>
<li>TypeScript</li>
<li>Vite</li>
<li>Tailwind CSS</li>
<li>React Router</li>
<li>Axios</li>
<li>Socket.IO Client</li>
<li>Recharts</li>
</ul>

<h3>Backend</h3>

<ul>
<li>Node.js</li>
<li>Express.js</li>
<li>MongoDB Atlas</li>
<li>Mongoose</li>
<li>JWT Authentication</li>
<li>Cookie Parser</li>
<li>Socket.IO</li>
<li>Cloudinary</li>
<li>Nodemailer</li>
</ul>

<h3>AI & Computer Vision</h3>

<ul>
<li>Google Gemini API</li>
<li>Flask</li>
<li>OpenCV</li>
<li>dlib</li>
<li>NumPy</li>
</ul>

<hr>

<h2>👥 Role Hierarchy</h2>

<table>
<tr>
<th>Role</th>
<th>Responsibilities</th>
</tr>

<tr>
<td><b>Super Admin</b></td>
<td>Create and manage Admin accounts</td>
</tr>

<tr>
<td><b>Admin</b></td>
<td>Verify alumni, manage events, regenerate face embeddings</td>
</tr>

<tr>
<td><b>Alumni</b></td>
<td>Professional networking, mentorship, communication</td>
</tr>

<tr>
<td><b>Student</b></td>
<td>Profile building, networking, achievements and project management</td>
</tr>
</table>

<hr>

<h2>🔐 Authentication & Security</h2>

<ul>
<li>JWT Access & Refresh Tokens</li>
<li>Cookie-Based Authentication</li>
<li>Role-Based Authorization</li>
<li>Password Hashing using bcrypt</li>
<li>OTP-Based Registration Verification</li>
<li>Protected API Routes</li>
</ul>

<hr>

<h2>📧 OTP Verification System</h2>

<ul>
<li>Email OTP Delivery</li>
<li>MongoDB TTL Expiration</li>
<li>Secure User Onboarding</li>
<li>Mandatory Verification Before Registration</li>
</ul>

<hr>

<h2>💬 Real-Time Chat System</h2>

<ul>
<li>One-to-One Messaging</li>
<li>Persistent Conversations</li>
<li>Socket.IO Integration</li>
<li>Authenticated WebSocket Connections</li>
<li>Instant Message Delivery</li>
</ul>

<hr>

<h2>🎉 AI-Powered Event Management</h2>

<p>
Admins can create events using simple descriptions while Gemini AI automatically generates structured event information.
</p>

<ul>
<li>Event Title</li>
<li>Description</li>
<li>Tags</li>
<li>Speaker Details</li>
<li>Organizer Information</li>
<li>Status Classification</li>
</ul>

<hr>

<h2>🔍 Smart User Discovery</h2>

<ul>
<li>Name-Based Search</li>
<li>Role-Based Search</li>
<li>Skill-Based Discovery</li>
<li>Professional Profile Filtering</li>
<li>Face Recognition Matching</li>
</ul>

<hr>

<h2>🧠 Face Recognition Search</h2>

<p>
A dedicated Flask microservice generates and stores 128-dimensional facial embeddings using dlib for intelligent alumni and student discovery.
</p>

<ul>
<li>Face Embedding Generation</li>
<li>Similarity Matching</li>
<li>Avatar-Based Search</li>
<li>Photo-Based User Discovery</li>
<li>Fallback Text Search</li>
</ul>

<hr>

<h2>📊 Profile Evaluation & Gamification</h2>

<p>
Students can evaluate their profiles through an AI-assisted scoring engine that measures multiple dimensions of growth and engagement.
</p>

<h3>Evaluation Categories</h3>

<ul>
<li>Technical Mastery</li>
<li>Project Power</li>
<li>Collaboration</li>
<li>Leadership</li>
<li>Innovation & Creativity</li>
<li>Problem Solving</li>
<li>Academic Endurance</li>
<li>Extracurricular Activities</li>
</ul>

<h3>Gamification Features</h3>

<ul>
<li>XP System</li>
<li>Level Progression</li>
<li>Radar Chart Analytics</li>
<li>AI-Powered Profile Enrichment</li>
</ul>

<hr>

<h2>📂 Student Portfolio Management</h2>

<ul>
<li>Projects</li>
<li>Skills</li>
<li>Work Experience</li>
<li>Achievements</li>
<li>Academic Information</li>
<li>Profile Analytics</li>
</ul>

<hr>

<h2>☁️ Media Management</h2>

<ul>
<li>Cloudinary Integration</li>
<li>Avatar Uploads</li>
<li>Event Banner Storage</li>
<li>Optimized Asset Delivery</li>
</ul>

<hr>

<h2>🤖 AI Integration</h2>

<h3>Google Gemini API</h3>

<ul>
<li>Event Schema Generation</li>
<li>Event Metadata Enrichment</li>
<li>Profile Analysis</li>
<li>Experience Classification</li>
<li>Skill Categorization</li>
<li>Profile Scoring Assistance</li>
</ul>

<hr>

<h2>📡 Core Features</h2>

✅ OTP Verification<br>
✅ Alumni Approval Workflow<br>
✅ JWT Authentication<br>
✅ Real-Time Chat<br>
✅ Event Management<br>
✅ AI Event Generation<br>
✅ Face Recognition Search<br>
✅ Profile Evaluation Engine<br>
✅ Cloudinary Media Storage<br>
✅ Role-Based Access Control

<hr>

<h2>🛠️ Installation</h2>

<h3>Backend</h3>

<pre>
cd SIH2025_Backend
npm install
npm run dev
</pre>

<h3>Frontend</h3>

<pre>
cd SIH2025_Frontend
npm install
npm run dev
</pre>

<h3>Face Recognition Service</h3>

<pre>
cd Face_recog_backend

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
python app.py
</pre>

<hr>

<h2>🌟 Future Enhancements</h2>

<ul>
<li>Video Calling</li>
<li>Internship Referral Portal</li>
<li>Job Board Integration</li>
<li>AI Career Guidance</li>
<li>Alumni Recommendation Engine</li>
<li>Mobile Application</li>
</ul>

<hr>

<h2>👨‍💻 Developed For</h2>

<p>
Smart India Hackathon (SIH) 2025
</p>

<p>
Building a smarter alumni–student ecosystem powered by AI, real-time communication, and intelligent networking.
</p>
