# AI Car Marketplace

This project is a customized version of an AI-powered Car Marketplace built using **Next.js 14**, **Prisma**, **TailwindCSS**, **NextAuth**, and more.

It is inspired by [Me Abhi Singh's], which provides an excellent walkthrough for building a modern full-stack AI-enabled application. I followed the tutorial for learning purposes and made personal modifications.

## 🚀 Features

- AI-powered car search with `ai-sdk`
- Image upload with ImageKit
- Authentication using `NextAuth.js` and `Prisma Adapter`
- Form handling with `react-hook-form` and validation with `zod`
- UI components from `Radix UI` and `shadcn/ui`
- Theme support with `next-themes`
- Carousel support using `embla-carousel`
- Responsive and optimized design using Tailwind CSS

## 🛠️ Technologies Used

- Next.js 14 (App Router)
- TypeScript
- TailwindCSS & shadcn/ui
- Prisma ORM with PostgreSQL
- NextAuth.js (Authentication)
- Zustand (State Management)
- AI SDK (Google + Vercel AI)
- ImageKit
- React Hook Form + Zod
- Radix UI

## 📁 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/your-username/ai-car-marketplace
cd ai-car-marketplace
Install dependencies:
npm install
Set up environment variables:
cp .env.example .env
# Then fill in the required keys in your .env file
Run the Prisma migration and generate client:
npx prisma generate
npx prisma migrate dev
Start the development server:
npm run dev
Visit http://localhost:3000 to view the app.
⚠️ This repository is for educational and personal learning purposes only. No commercial use is intended.
