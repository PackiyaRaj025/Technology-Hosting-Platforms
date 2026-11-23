# 🚀 Hosting Platforms Guide

A beginner-friendly reference for deploying applications on modern cloud platforms — no physical server required. This document covers **Frontend**, **Backend**, and **Database** hosting options, along with their free tiers and credit card requirements.

> 📚 Part of my learning journey — documenting technology hosting platform details.

---

## 📑 Table of Contents

- [Frontend Hosting](#-frontend-hosting)
- [Backend Hosting](#-backend-hosting)
- [Database Hosting](#-database-hosting)
- [Recommendation for Beginners](#-recommendation-for-beginners)
- [Quick Comparison Cheat Sheet](#-quick-comparison-cheat-sheet)

---

## 🎨 Frontend Hosting

Deploy static sites and frontend frameworks like React, Vue, Angular, and Next.js.

| Platform | Best For | Free Tier | Credit Card? |
|----------|----------|-----------|--------------|
| **Vercel** | React, Vue, Angular, Next.js, Vite | 100 GB bandwidth/month, unlimited deploys | ❌ No |
| **Netlify** | Static sites, React, Vue, Angular | 100 GB bandwidth/month, 300 build min | ❌ No |
| **GitHub Pages** | Static HTML/CSS/JS, simple sites | Unlimited (public repos) | ❌ No |
| **Cloudflare Pages** | Any static frontend | Unlimited requests | ❌ No |

---

## ⚙️ Backend Hosting

Host APIs and server-side applications written in Node.js, Python, Ruby, Go, Rust, or any language.

| Platform | Best For | Free Tier | Credit Card? |
|----------|----------|-----------|--------------|
| **Render** | Node.js, Python, Ruby, Go, Rust | 750 hrs/month, sleeps after 15 min | ✅ Yes ($1 hold, refunded) |
| **Railway** | Any language/framework | $5 credit/month | ❌ No (after trial) |
| **Fly.io** | Containerized apps (Docker) | 3 shared VMs free | ❌ No |
| **Koyeb** | Node.js, Python, Docker | 1 free service | ❌ No |

---

## 🗄️ Database Hosting

Managed database services — no server setup required.

| Platform | Best For | Free Tier |
|----------|----------|-----------|
| **MongoDB Atlas** | MongoDB (NoSQL) | 512 MB storage forever |
| **Supabase** | PostgreSQL + Auth + Storage | 500 MB database |
| **PlanetScale** | MySQL | 5 GB storage |
| **Neon** | PostgreSQL | 512 MB storage |
| **ElephantSQL** | PostgreSQL | 20 MB (tiny projects) |

---

## 🎯 Recommendation for Beginners

> **Use [Vercel](https://vercel.com) for your frontend and [Render](https://render.com) for your backend.**

Both are:

- ✅ **Beginner-friendly** with simple setup
- ✅ **Generous free tiers** to start without spending money
- ✅ **Directly connected to GitHub** for automatic deployments

---

## 📊 Quick Comparison Cheat Sheet

| Category | Top Pick | Why |
|----------|----------|-----|
| **Frontend** | Vercel | Best framework support, no credit card |
| **Backend** | Render | Multi-language, easy GitHub integration |
| **Database** | Supabase | PostgreSQL + Auth + Storage in one |
| **Docker Apps** | Fly.io | 3 free VMs, container-ready |
| **Static Sites** | Cloudflare Pages | Unlimited requests, fast global CDN |

---

## 🔗 Useful Links

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [GitHub Pages](https://pages.github.com)
- [Cloudflare Pages](https://pages.cloudflare.com)
- [Render](https://render.com)
- [Railway](https://railway.app)
- [Fly.io](https://fly.io)
- [Koyeb](https://koyeb.com)
- [MongoDB Atlas](https://www.mongodb.com/atlas)
- [Supabase](https://supabase.com)
- [PlanetScale](https://planetscale.com)
- [Neon](https://neon.tech)
- [ElephantSQL](https://elephantsql.com)

---

## 📝 Notes

- Free tiers can change over time — always verify on the official platform website.
- "Sleeps after 15 min" on Render means the app goes idle but wakes on request (cold start delay).
- GitHub Pages only supports static content — no server-side code.

---

*Last updated: 2026 | Part of my technology learning journey ✨*
