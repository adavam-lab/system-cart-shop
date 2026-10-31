# ADAVAM - E-Commerce & Admin Dashboard

Welcome to the ADAVAM project! This repository contains a full-stack e-commerce solution with multiple frontend interfaces and a robust backend API.

## 📸 Galería del Proyecto

<p align="center">
  <img src="img/slide.gif" alt="Galería del proyecto ADAVAM" width="900" />
</p>

---

## 🚀 Prerequisites

- Node.js
- npm or yarn
- PostgreSQL (Database)

## 🛠️ Getting Started

Since `node_modules` are gitignored, you will need to install the dependencies for the projects you are working on.

Navigate to the respective directory and install the dependencies:

```bash
# Example for the Admin frontend project
cd frontend-admin
npm install
npm run dev

# Example for the Client Flowbite project
cd frontend-flowbite
npm install
npm run dev

# Example for the backend API
cd api
npm install
npm run dev
```

## 🔐 Environment Variables

This project uses environment variables. Do not commit `.env` files. Instead, create a `.env.test` or `.env.example` file that contains the variable names without sensitive values. 

A `.env.test` has been created for your convenience in the corresponding folders. Make sure to copy it to `.env` and fill in the necessary values before running the application.

```bash
cp .env.test .env
```
