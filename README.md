#  Job Tracker

A modern **Job Tracking and Application Management** platform built with **Next.js, Prisma, and Tailwind CSS**.  
It helps users efficiently manage, categorize, and monitor their job applications in one place — with an elegant UI and AI-powered insights.

---

##  Live Demo
 [https://job-tracker.vercel.app](https://job-tracker.vercel.app)

---

##  Overview

**Job Tracker** enables users to:
- Log job applications (company, role, status, date, notes)
- Track progress through different application stages
- Visualize statistics and trends over time
- Manage data securely using **Prisma + SQLite**
- Authenticate with modern **NextAuth** flow
- Enjoy a responsive, modern UI built with **Tailwind CSS + ShadCN UI**

---

##  Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | Next.js (App Router) |
| **Backend** | Next.js API Routes + Prisma ORM |
| **Database** | SQLite (development) |
| **Authentication** | NextAuth.js |
| **Styling** | Tailwind CSS + Radix UI + Lucide Icons |
| **State Management** | React Hooks + Context |
| **Data Visualization** | Nivo / Recharts |
| **AI Integration** | LangChain + OpenAI (optional) |
| **Testing** | Jest + Playwright |
| **Deployment** | Vercel |

---

##  Features

✅ Add, edit, and delete job applications  
✅ Filter and categorize by company, status, or date  
✅ Visual dashboard for job stats  
✅ Secure user authentication  
✅ Responsive, minimal UI  
✅ AI-assisted job summary (optional)  

---

##  Getting Started (Local Setup)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Kushagra001/Job-Tracker.git
cd Job-Tracker
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file:
```
DATABASE_URL="file:./prisma/data/dev.db"
NEXTAUTH_SECRET="your_secret_key"
OPENAI_API_KEY="your_api_key"   # optional
```

### 4️⃣ Initialize Database
```bash
npx prisma migrate dev --name init
npm run seed
```

### 5️⃣ Run Development Server
```bash
npm run dev
```
Visit: [http://localhost:3000](http://localhost:3000)

---

##  Testing

Run unit tests:
```bash
npm run test
```

Run end-to-end tests:
```bash
npm run test:e2e
```

---

##  Deployment

Easily deploy on **Vercel**:
- Push to GitHub → import repo to [Vercel](https://vercel.com/)
- Set `.env` variables in dashboard
- Build Command: `npm run build`
- Output Directory: `.next`

---

## 👨 Author

**Kushagra Singh Negi**  
🎓 MCA Student | 💻 Full Stack Developer  
🔗 [GitHub](https://github.com/Kushagra001) • [LinkedIn](https://www.linkedin.com/in/kushagra001)

---

## 🪪 License
This project is open-source under the **MIT License**.  
Feel free to use and modify with attribution.

---

> Built with ❤️ by Kushagra Singh Negi — Next.js, Prisma, and Tailwind CSS
