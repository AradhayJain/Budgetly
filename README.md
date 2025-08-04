<h1 align="center">🧾 Budgetly – Smart Budget & Expense Manager 💸</h1>

<p align="center">
  <b>AI-powered personal finance manager that helps you track income, control expenses, and save smarter.</b>
</p>

---

<h2>🌟 Features</h2>

<ul>
  <li>📊 <b>Dashboard Overview</b>: Visual insights into total income, expenses, savings, and budget balance.</li>
  <li>🔍 <b>AI Insights</b>: Automatically generates monthly savings suggestions based on your spending patterns.</li>
  <li>💼 <b>Income & Expense Tracking</b>: Add, edit, and delete income sources and categorized expenses.</li>
  <li>💸 <b>Spending Limits</b>: Set monthly and per-category budget limits with visual tracking.</li>
  <li>🏅 <b>Badges & Rewards</b>: Earn badges for good financial behavior, such as staying within limits.</li>
  <li>👥 <b>Group Savings</b>: Collaborate with friends or family in shared savings groups with live chat.</li>
  <li>🧠 <b>AI Chat Assistant</b>: Built-in chatbot for financial advice and queries.</li>
  <li>📈 <b>Analytics Page</b>: Daily expense graphs and category-based trend analysis.</li>
  <li>📱 <b>Fully Responsive</b>: Seamless experience on mobile, tablet, and desktop.</li>
</ul>

---

<h2>🛠️ Tech Stack</h2>

<h4>Frontend</h4>

<ul>
  <li>React.js (Vite)</li>
  <li>Tailwind CSS</li>
  <li>Framer Motion (Animations)</li>
  <li>Chart.js / Recharts (Graphs)</li>
  <li>Axios</li>
</ul>

<h4>Backend</h4>

<ul>
  <li>Node.js + Express</li>
  <li>MongoDB + Mongoose</li>
  <li>WebSockets for real-time messaging</li>
</ul>

<h4>AI/ML</h4>

<ul>
  <li>Custom AI model for budgeting suggestions</li>
</ul>

---

<h2>📁 Project Structure</h2>

<pre>
Budgetly/
├── client/                 # Frontend (React)
│   ├── components/
│   ├── pages/
│   ├── context/
│   └── App.jsx
├── server/                 # Backend (Node.js + Express)
│   ├── models/
│   ├── routes/
│   ├── sockets/
│   └── server.js
├── README.md
└── package.json
</pre>

---

<h2>🚀 Getting Started</h2>

<h4>Prerequisites</h4>
<ul>
  <li>Node.js v18+</li>
  <li>MongoDB Atlas (or local instance)</li>
  <li>Optional: OpenAI API key</li>
</ul>

<h4>Installation</h4>

<pre>
# Clone the repo
git clone https://github.com/your-username/budgetly.git
cd budgetly

# Install dependencies
cd client
npm install

cd ../server
npm install
</pre>

<h4>Configure .env in /server:</h4>

<pre>
MONGO_URL=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
PORT=5000
</pre>

<h4>Start the app:</h4>

<pre>
# Backend
npm run dev

# Frontend (in a separate terminal)
cd ../client
npm run dev
</pre>

Now visit <code>http://localhost:5173</code> in your browser.

---

<h2>🔒 Security</h2>

<ul>
  <li>Passwords (if added) are hashed using bcrypt</li>
  <li>JWT or session-based authentication</li>
  <li>Input validation + Secure CORS config</li>
</ul>

---

<h2>📈 Future Plans</h2>

<ul>
  <li>📲 Mobile App (React Native)</li>
  <li>🧠 Advanced AI forecasting</li>
  <li>🏦 Bank integrations (Plaid API)</li>
  <li>🔔 Spending alerts</li>
  <li>🌍 Multi-language support</li>
</ul>

---

<h2>🤝 Contributing</h2>

<p>We welcome contributions! Please open issues or submit pull requests to help improve Budgetly.</p>

---

<h2>📜 License</h2>

<p>MIT License © 2025 Aradhay Jain</p>
