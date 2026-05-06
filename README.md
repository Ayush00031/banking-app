💳 Banking App

A modern full-stack banking application built with Next.js 14, TypeScript, Tailwind CSS, Appwrite, Plaid, and Dwolla.
The application allows users to securely connect bank accounts, view transactions, transfer money, and monitor financial activity through an elegant dashboard.

🚀 Features
🔐 Secure Authentication System
🏦 Connect Bank Accounts using Plaid
💸 Transfer Funds with Dwolla Integration
📊 Financial Dashboard with Charts & Analytics
📈 Expense & Transaction Tracking
📱 Fully Responsive UI
⚡ Fast Performance with Next.js 14 App Router
🎨 Modern UI using Tailwind CSS + Radix UI
🧾 Form Validation using React Hook Form + Zod
📉 Interactive Charts using Chart.js
🛡️ Error Monitoring with Sentry
🛠️ Tech Stack
Frontend
Next.js 14
React 18
TypeScript
Tailwind CSS
Radix UI
Chart.js
React Hook Form
Zod
Backend & Services
Appwrite
Plaid API
Dwolla API
Sentry
📦 Dependencies

Some major libraries used in the project:

next
react
typescript
tailwindcss
chart.js
react-chartjs-2
react-hook-form
zod
plaid
dwolla-v2
node-appwrite
@sentry/nextjs
📂 Project Structure
banking-app/
│── app/
│── components/
│── constants/
│── lib/
│── public/
│── styles/
│── types/
│── package.json
│── tailwind.config.ts
│── next.config.js
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/ayushrawat00031/banking-app.git
2️⃣ Navigate to the Project
cd banking-app
3️⃣ Install Dependencies
npm install
4️⃣ Setup Environment Variables

Create a .env.local file in the root directory and add:

NEXT_PUBLIC_APPWRITE_ENDPOINT=
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=

PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=sandbox

DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_ENV=sandbox

SENTRY_AUTH_TOKEN=
▶️ Running the App
Development Mode
npm run dev
Production Build
npm run build
npm start
📊 Banking Dashboard

The application includes:

Account balance overview
Transaction history
Expense analytics
Money transfer functionality
Interactive charts and graphs
🔒 Security Features
Secure API integrations
Protected routes
Form validation
Error tracking with Sentry
Environment variable protection

🤝 Contributing

Contributions are welcome!

Fork the repository
Create a feature branch
git checkout -b feature-name
Commit changes
git commit -m "Added new feature"
Push to GitHub
git push origin feature-name
Open a Pull Request
📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Ayush Rawat
