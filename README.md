# 📝 Tracktide App - Full Stack AI-Powered Journal

![Next.js](https://img.shields.io/badge/Next.js-15-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-2.2-38b2ac?logo=tailwindcss)
![Shadcn UI](https://img.shields.io/badge/Shadcn--UI-Components-orange)
![Clerk](https://img.shields.io/badge/Clerk-Auth-3B82F6?logo=clerk)
![NeonDB](https://img.shields.io/badge/NeonDB-PostgreSQL-green?logo=postgresql)
![Arcjet](https://img.shields.io/badge/Arcjet-Security-critical?logo=security)

## 🚀 Overview

This is a modern, secure, and AI-integrated journal app built using the latest web technologies:

* **Next.js 15 (App Router)**
* **Tailwind CSS + Shadcn UI**
* **Clerk for Auth**
* **NeonDB with Prisma ORM**
* **Arcjet for API protection and rate limiting**

Users can create journal entries, tag moods, analyze emotional trends, and organize thoughts into collections. The project follows scalable architecture best practices, emphasizing performance, security, and developer productivity.

## ✨ Features

* 🔐 **User Authentication & Route Protection** with Clerk
* 📘 **Rich Text Journaling** powered by `react-quill`
* 📊 **Mood Analytics** via Recharts (daily averages, trends, visual scores)
* 🗂️ **Organize Entries into Collections** (create/delete)
* 📝 **Draft & Edit Functionality** with auto-save
* 🖼️ **Pixabay Integration** for auto-image generation per mood
* 🛡️ **Arcjet Middleware** for rate limiting & bot protection

## 🧠 Tech Stack

| Category           | Tech                                           |
| ------------------ | ---------------------------------------------- |
| Frontend Framework | Next.js 15 (App Router + TurboPack + React 19) |
| Styling            | Tailwind CSS, Shadcn UI                        |
| Authentication     | Clerk                                          |
| Database           | NeonDB (PostgreSQL), Prisma ORM                |
| API Rate Limiting  | Arcjet                                         |
| Charting           | Recharts                                       |
| Form Validation    | react-hook-form, Zod                           |
| Rich Text Editor   | react-quill                                    |
| Image API          | Pixabay API integration                        |
| Date Utilities     | date-fns                                       |

## 📁 Folder Structure

```
/app
 └── auth
 └── dashboard
 └── journal
 └── (main)
 └── (auth)
 └── _components
 └── layout.js
 └── page.js
/lib
 └── prisma.ts
 └── checkUser.ts
 └── arcjet.ts
/middleware.js
/prisma
 └── schema.prisma
```

## 📦 Installation

```bash
git clone https://github.com/sohithk2002/Tracktide.git
cd Tracktide
pnpm install
```

```

## 🔒 Middleware Highlights

* Protected routes: `/dashboard`, `/journal`, `/collection`
* `middleware.js` checks for user via Clerk and protects from bots with Arcjet
* Arcjet shields routes from common attacks

## 📈 Analytics

![Mood Analytics Screenshot](https://yourcdn.com/screenshot1.png)
![Journal Interface](https://yourcdn.com/screenshot2.png)

## 🙌 Acknowledgments

* Inspired by the community project walkthrough by Fireship
* Clerk for seamless auth experience
* Shadcn for beautiful UI boilerplates
* Arcjet for taking care of security

---

Built with ❤️ by Sohith Kampalli
