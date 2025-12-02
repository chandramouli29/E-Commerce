🛒 Django E-Commerce Web Application
This repository contains a fully functional e-commerce platform built using Django, HTML5, CSS3, and JavaScript. The application provides secure user authentication, product catalog browsing, cart operations, order workflow, and admin-side control. It is designed with clean, modular code ensuring scalability and smooth performance.

🚀 Features
🧑‍💻 User-Side
	• 🔐 User Authentication – Register, Login, Logout
	• 🛍️ Product Listings – Dynamic display with images
	• 🛒 Cart Management – Add, remove, and update items
	• 💳 Order Flow – Complete ordering pipeline
	• 📱 Responsive UI – Optimized for mobile, tablet, and desktop
	• 🔎 Product Details – Description, price, stock info
🛠️ Admin-Side
	• 📦 Add/Edit/Delete Products
	• 🖼️ Product image uploads
	• 📊 Manage stock and pricing

🧱 Tech Stack
Frontend: HTML5, CSS3
Backend: Python, Django
Database: SQLite /dbsql lite3(Django include)
Tools: VS Code, Git
Version Control: Git & GitHub

🌟 Future Enhancements
	• 🏷️ Category-wise product filtering
	• 💰 Razorpay or Stripe payment gateway
	• 🔄 Order history & invoice generation
	• ⭐ Product rating & review system
	• 🔐 Enhanced security (CAPTCHA, OTP login)
	• 📦 Wishlist & Save-for-Later
	• 🌍 Multi-language support (i18n)
	• ☁️ Deployment on AWS/Render/Vercel

🧩 Development Process
1️⃣ Project Setup
Installed Django using:

pip install django
Created project:

django-admin startproject ecommerce
Created main apps for products, users, and cart:

python manage.py startapp products
python manage.py startapp users
python manage.py startapp cart

2️⃣ Project Configuration
settings.py updates:
	• Registered apps inside INSTALLED_APPS
	• Configured STATICFILES_DIRS
	• Added MEDIA_URL & MEDIA_ROOT for image uploads
	• Linked templates folder using TEMPLATES
urls.py setup:
	• Included routes for products, users, and cart
	• Configured media settings during development

3️⃣ Templates & Static Integration
	• Created base templates (base.html, index.html, products.html)
	• Used {% load static %} to link CSS, JS
	• Added responsive design using Flexbox & Grid
	• Implemented interactive elements via JavaScript

4️⃣ Core Modules
🛍️ Products Module
	• Store product details
	• Image upload support
	• Stock tracking
🛒 Cart Module
	• Session-based cart operations
	• Add/Remove/Update items
	• Auto total calculation
👤 User Module
	• Registration with validation
	• Login/Logout (Django Auth)
	• User session management

5️⃣ Admin Panel
	• Added models to Django admin
	• Enabled product creation with image upload
	• Provided stock & price controls
	• Integrated product filtering

6️⃣ Version Control

git init
git add .
git commit -m "Initial E-Commerce Setup"
git push origin main

7️⃣ Testing & Optimization
	• Tested all shopping flows
	• Ensured mobile responsiveness
	• Validated HTML & CSS
	• Improved load time by optimizing images

8️⃣ Deployment (Upcoming)
Deployment plans include:
	• Render / Vercel with Django backend
	• Custom domain + SSL
	• Cloud database integration

🏁 Outcome
This project demonstrates:
	• Strong Django backend architecture
	• Clear understanding of product & cart workflows
	• Integration of UI with backend logic
	• Ability to build scalable web applications

👤 Author Information
Name: Chandra Mouli S T
College: M.Kumarasamy College of Engineering
Department: B.Tech Information Technology
Role: Software Engineer (Python Full Stack Developer)
Email: mouligavaaskar@gmail.com
LinkedIn: linkedin.com/in/chandramouli-st
