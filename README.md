# Woice AI 🎤

Woice AI is a full-stack AI-powered Text-to-Speech platform that allows users to generate voice from text, manage voice libraries, and experiment with speech parameters.

## 🚀 Features

- Text-to-Speech generation interface
- Voice library with multiple system voices
- Adjustable parameters (creativity, expression, flow)
- Authentication using Clerk
- Scalable backend using tRPC and Prisma
- PostgreSQL database (Neon)

## 🛠️ Improvements Made

- Removed billing system (Polar integration)
- Refactored backend to support free usage
- Migrated to Prisma v7 configuration
- Implemented fallback for missing cloud services (R2, Modal)
- Fixed seed scripts to run without external dependencies
- Cleaned and customized project structure

## ⚙️ Tech Stack

- Next.js
- TypeScript
- Prisma
- Neon PostgreSQL
- tRPC
- Tailwind CSS

## 📌 Status

⚠️ AI voice generation requires external services (Modal + R2) to be fully functional.

## 🧠 Learning Outcome

This project helped me understand:
- Full-stack SaaS architecture
- Backend API design with tRPC
- Database integration with Prisma
- Handling missing cloud dependencies gracefully
- Refactoring and customizing large codebases

---

Built by Prince Jha 🚀