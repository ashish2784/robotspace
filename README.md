# Robotspace website clone – Documentation & Developer Guide

Robotspace is an OEM-backed robotics, IIoT, and low‑cost automation platform built with in‑house R&D, support, and manufacturing. This repository contains the **Robotspace web application**, built using **SvelteKit**, and serves as the digital interface for product exploration, configuration, and integrations with third‑party systems.

---


---

## 📁 Project Structure (SvelteKit Overview)

The app is built using **SvelteKit**, following recommended conventions. Below is an overview of core project folders:



### Key Design Notes

- **File-based routing** → automatic page creation based on folder structure  
- **Load functions** used for data fetching  
- **Layouts** used for consistent header/footer/themes  
- **Static folder** used for downloadable documents, icons, product imagery  

---

## 🛠️ Development Setup

### 1. **Install dependencies**
Ensure you have Node.js 18+ installed.

```bash
npm install
```

### 2. **Start development server**

```bash
npm run dev
```

This starts SvelteKit in development mode.  
The app will run at:

```
http://localhost:5173
```

(with HMR for instant updates)

---

## 🏗️ Build Instructions

To generate a production build:

```bash
npm run build
```

This outputs optimized production assets inside:

```
/build
```

---

## 🚢 Deployment

Robotspace (SvelteKit) can be deployed on multiple platforms. Common deployment targets include:

### **1. Node Server Deployment**

```bash
npm run build
node build
```

You may configure a reverse proxy (NGINX/Apache) to serve HTTPS and static content.

### **2. Static Deployment (if using adapter-static)**

If configured in `svelte.config.js`:

```bash
npm run build
npm run preview
```

Deploy the generated files in `/build` to any static host (Netlify, Vercel, S3, Cloudflare Pages).

### **3. Vercel Deployment**

Install the adapter:

```bash
npm install -D @sveltejs/adapter-vercel
```

Push to GitHub → Import into Vercel → Deploy automatically.

### **4. Docker Deployment (optional)**

```
docker build -t robotspace .
docker run -p 3000:3000 robotspace
```

---

© Ashish Manoj 2025
