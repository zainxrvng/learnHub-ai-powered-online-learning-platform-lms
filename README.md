# 🎓 LearnHub | AI-Powered Online Learning Platform (LMS)

![Next.js](https://img.shields.io/badge/Next.js-14+-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css)

[cite_start]**LearnHub** is a production-ready, full-stack Learning Management System (LMS) built using the Next.js 14 App Router[cite: 4, 21]. [cite_start]It features a multi-role architecture for students and instructors, real-time progress tracking, and an integrated AI study assistant to simplify complex concepts[cite: 23, 30].

---

## 🚀 Key Features

### 👨‍🎓 For Students
* [cite_start]**Course Discovery**: Browse, search, and filter courses by category, difficulty level, and price[cite: 23, 236].
* [cite_start]**Interactive Learning**: A seamless lesson player with video integration and sidebar navigation[cite: 236, 292].
* [cite_start]**Progress Tracking**: Persistent tracking of completed lessons with visual progress bars[cite: 23, 29].
* [cite_start]**AI Study Assistant**: Get simplified explanations and analogies for difficult technical concepts[cite: 23, 254].

### 👨‍🏫 For Instructors
* [cite_start]**Course Builder**: Create and edit courses with organized chapters and lessons[cite: 27, 236].
* [cite_start]**Content Management**: Manage video URLs, descriptions, and rich-text lesson content[cite: 27, 177].
* [cite_start]**Publishing Workflow**: Validation-based flow to ensure courses are complete before going live[cite: 253].

### 🛡️ Core Infrastructure
* [cite_start]**Role-Based Access**: Secure dashboards tailored for Student, Instructor, and Admin personas[cite: 25, 30].
* [cite_start]**Responsive Design**: Mobile-first UI with Dark Mode support for late-night study sessions[cite: 266, 267].
* [cite_start]**Auth Integration**: Secure authentication via Google OAuth and email/password credentials[cite: 6, 107].

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Framework** | [cite_start]**Next.js 14+** (App Router, Server Components, Server Actions) [cite: 4, 50, 249] |
| **Language** | [cite_start]**TypeScript** for robust type safety [cite: 4, 41] |
| **Database** | [cite_start]**PostgreSQL** with **Prisma ORM** [cite: 5, 41] |
| **Auth** | [cite_start]**NextAuth.js** (Auth.js) [cite: 6, 41] |
| **Styling** | [cite_start]**Tailwind CSS** + **shadcn/ui** [cite: 5, 45] |
| **AI** | [cite_start]**Vercel AI SDK** / Template-based Concept Explainer [cite: 41, 254] |
| **Deployment** | [cite_start]**Vercel** with automatic CI/CD [cite: 6, 45] |

---

## 📂 Database Schema

[cite_start]The application utilizes a relational PostgreSQL database managed via Prisma[cite: 5]. Key models include:
* [cite_start]**User**: Manages student and instructor profiles with role-based flags[cite: 114, 226].
* [cite_start]**Course**: Contains metadata, pricing, and instructor associations[cite: 138].
* [cite_start]**Chapter**: Individual lessons linked to courses with ordering logic[cite: 170].
* [cite_start]**Progress**: Tracks the completion status of chapters per user[cite: 213, 244].

---

## 🏁 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/learnhub.git](https://github.com/your-username/learnhub.git)
cd learnhub
