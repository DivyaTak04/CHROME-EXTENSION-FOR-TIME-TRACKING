# CHROME EXTENSION FOR TIME TRACKIING ⏱️
A Productivity-focused Chrome Extension that tracks the user's time spent on different websites with a full-stack backend using Node.js, Express, and MongoDB, along with a React.js dashboard to visualize user analytics.

## 🚀 Features
🧠 Automatically tracks time spent on websites

⏱ Logs start/end time, total active time, and website title

💤 Idle time detection

📊 Dashboard with charts (bar + pie)

📅 Filters for Today / This Week / This Month

🔐 User authentication with JWT

📤 Export activity as CSV

🌗 Clean and modern UI with dark mode

🛠 Backend APIs to store & fetch activity logs

## 🧪 Tech Stack
Frontend Dashboard: React.js,CSS 

Chrome Extension: JavaScript, Chrome APIs

Backend: Node.js, Express.js, MongoDB

## 📸 Screenshots
<img width="1888" height="903" alt="image" src="https://github.com/user-attachments/assets/5f0110d6-b13f-436f-9121-68e7321e7a9c" />

<img width="1872" height="905" alt="image" src="https://github.com/user-attachments/assets/0ccf3a87-1315-4ed1-9629-6b1ed66f83ee" />

<img width="1870" height="912" alt="image" src="https://github.com/user-attachments/assets/78b4b021-8f85-4406-a84f-f2b6993be314" />

## 📦 Installation & Setup
1. Clone the repository:

   git clone https://github.com/DivyaTak04/CHROME-EXTENSION-FOR-TIME-TRACKING.git
   
   cd time-tracker-extension

3. Install backend dependencies:

   cd backend
   npm install

4. Install frontend dashboard dependencies:

   cd ../frontend-dashboard
   npm install

5. Setup .env in the backend folder:
   Create a .env file:

   MONGODB_URI=your_mongodb_connection_string
   
   PORT=5000

7. Run the backend server:

   npm run dev

8. Run the frontend dashboard:

   npm start

9. Load Chrome Extension:

   Go to chrome://extensions/
   
   Enable "Developer mode"
   
   Click “Load unpacked” and select the extension folder

## 📌 About Me
Hi! I’m Divya Tak, a passionate full-stack developer and intern who enjoys creating modern, responsive web apps and browser extensions. This project showcases my ability to combine Chrome Extension APIs with full-stack development skills using React, MongoDB, and Node.js.
