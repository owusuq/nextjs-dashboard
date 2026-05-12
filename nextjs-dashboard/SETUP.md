# Next.js Dashboard – WDD430 Complete Project

This is the **fully completed** Next.js Dashboard tutorial (all 16 chapters).

---

## 🚀 Quick Start in VS Code

### 1. Install dependencies
```bash
npm install
```

### 2. Set up your database (Vercel Postgres)
- Go to [vercel.com](https://vercel.com) → Storage → Create Database → Postgres
- After creating, go to the `.env.local` tab and copy all values
- Paste them into the `.env.local` file in this project

### 3. Seed the database
Once `.env.local` is filled in, visit:
```
http://localhost:3000/seed
```
This populates your database with sample data.

### 4. Run the dev server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000)

---

## 🔐 Login Credentials (after seeding)
- **Email:** user@nextmail.com  
- **Password:** 123456

---

## 📁 Project Structure
```
app/
  dashboard/        ← Dashboard pages (overview, invoices, customers)
  login/            ← Login page
  lib/              ← Data fetching, actions, utils
  ui/               ← All UI components
  seed/             ← Database seed route
auth.ts             ← NextAuth configuration
auth.config.ts      ← Auth middleware config
```

---

## ✅ Chapters Covered
1. Getting Started
2. CSS Styling
3. Optimizing Fonts & Images
4. Creating Layouts & Pages
5. Navigating Between Pages
6. Setting Up Your Database
7. Fetching Data
8. Static & Dynamic Rendering
9. Streaming
10. Partial Prerendering
11. Search & Pagination
12. Mutating Data (Server Actions)
13. Handling Errors
14. Accessibility & Form Validation
15. Authentication (NextAuth.js)
16. Metadata

---

## 🌐 Deploy to Vercel
1. Push to GitHub
2. Import repo on [vercel.com](https://vercel.com)
3. Add environment variables from your Postgres DB
4. Deploy — copy the URL and submit to Canvas
