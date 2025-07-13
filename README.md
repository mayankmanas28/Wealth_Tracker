# 💰 Wealth Tracker 

A simple yet powerful **personal finance management web app** that helps users track expenses, manage income, and gain insights into their financial health. This app was built as part of an internship project using **modern full-stack tools** like Next.js, Prisma, Supabase, and Clerk.

---

## 📌 Features

- 🔐 User Authentication (Clerk)
- 📊 Track Incomes and Expenses
- 💼 Manage Multiple Bank Accounts
- 🗂 Categorize Transactions
- 📅 Set Recurring Payments
- 📷 OCR-based Receipt Scanning
- 🌐 ₹ / $ Currency Toggle
- 📈 Dashboard Overview with Recent Activity

---

## 🛠️ Tech Stack

| Area               | Tool/Framework             |
|--------------------|----------------------------|
| Frontend           | Next.js (App Router)       |
| UI Components      | TailwindCSS + ShadCN       |
| Forms              | React Hook Form + Zod      |
| Backend            | Prisma ORM                 |
| Database           | Supabase (PostgreSQL)      |
| Auth               | Clerk.dev                  |
| State/Utils        | useFetch Hook, Context API |
| Currency Toggle    | Context + Intl Formatting  |
| Deploy             | Vercel (Recommended)       |

---

.
├── app/                     # Routes (App Router)
├── components/              # UI Components
├── lib/                     # DB, utilities
├── actions/                 # Server actions
├── prisma/                  # Prisma schema
├── hooks/                   # Custom React hooks
├── public/                  # Static assets
├── emails/                 # Email templates
├── tailwind.config.js       # Tailwind config
└── package.json

