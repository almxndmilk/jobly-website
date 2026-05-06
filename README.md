# Jobly Website

A modern job platform web application built with Next.js and Supabase.

## 🚀Features

* User authentication
* Job listings and browsing
* Responsive modern UI
* Database integration with Supabase
* Fast development with Next.js

## 🛠️Tech Stack

* **Frontend:** Next.js 16
* **Language:** TypeScript
* **Backend / Database:** Supabase
* **Package Manager:** pnpm
* **Styling:** CSS / Tailwind CSS (if applicable)

## ⚙️Getting Started

### Prerequisites

Install the following before running the project:

* Node.js v20+
* pnpm
* Supabase account

Install pnpm globally:

```bash
npm install -g pnpm
```

---

## ⚙️Installation

Clone the repository:

```bash
git clone <your-repo-url>
cd jobly-website
```

Install dependencies:

```bash
pnpm install
```

---

## ⚡Environment Variables

Create a file named:

```txt
.env.local
```

Add the following:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_publishable_key
```

You can find these values in:

```txt
Supabase Dashboard → Project Settings → API Keys
```

---

## 🌐Running the Development Server

Start the app:

```bash
pnpm dev
```

Open your browser:

```txt
http://localhost:3000
```

---

## 💻Project Structure

```txt
jobly-website/
├── app/
├── components/
├── lib/
├── public/
├── styles/
├── .env.local
├── package.json
├── pnpm-lock.yaml
└── next.config.mjs
```

---

## 👨🏻‍💻Common Issues

### Port Already In Use

Kill running Node processes:

```powershell
taskkill /F /IM node.exe
```

Then restart:

```bash
pnpm dev
```

---

### Supabase Environment Variable Error

Make sure `.env.local` exists and contains valid values:

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

Restart the development server after updating environment variables.

---

## 💡Deployment with Vercel

1. Push your project to GitHub:

```bash
git add .
git commit -m "Initial deploy"
git push
```

2. Go to Vercel and sign in with GitHub.

3. Import your repository.

4. Add the following environment variables in Vercel:

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

5. Deploy the project.

Your deployed website will receive a public URL such as:

```txt
https://jobly-website.vercel.app
```

---

## 🤖Build for Production

```bash
pnpm build
```

Run production build:

```bash
pnpm start
```

---

## 🤝Future Improvements

* Job application tracking
* User dashboards
* Admin management panel
* Search and filtering
* Email notifications
* Deployment to Vercel

---

## 📄License

This project is for educational and development purposes.
