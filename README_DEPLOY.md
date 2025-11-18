# 🚀 Kemixall Deployment Guide

This guide helps you deploy the **Kemixall e-commerce site** instantly.

## 1️⃣ Backend (Render)
1. Visit https://render.com
2. Click **New Web Service**
3. Connect your GitHub repo
4. It will auto-detect `render.yaml`
5. Click **Deploy**

Your backend API will be live at:
https://kemixall-backend.onrender.com/api/products

## 2️⃣ Frontend (Vercel)
1. Visit https://vercel.com
2. Create a new project
3. Select your GitHub repo
4. Set **Root Directory = frontend**
5. Add environment variable:
REACT_APP_API_URL=https://kemixall-backend.onrender.com
6. Click **Deploy**

Your frontend will be live at:
https://kemixall.vercel.app

## 3️⃣ Stripe (Test Payments)
Use Stripe test cards for payment simulation:
Card Number: 4242 4242 4242 4242
Exp Date: Any future date
CVC: Any 3 digits
ZIP: Any 5 digits

View payments in your Stripe test dashboard.

### ✅ DONE!
Frontend: https://kemixall.vercel.app
Backend: https://kemixall-backend.onrender.com
DB: MongoDB Atlas
Payment: Stripe (Test Mode)
