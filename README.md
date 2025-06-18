


<h1 align="center">📚 StudyNotion</h1>
<p align="center">
  A full-featured EdTech platform built with the MERN stack, empowering users to create, consume, rate, and manage educational content.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/pratham145/StudyNotion?style=for-the-badge&color=yellow" alt="Stars" />
  <img src="https://img.shields.io/github/forks/pratham145/StudyNotion?style=for-the-badge&color=blueviolet" alt="Forks" />
  <img src="https://img.shields.io/github/license/pratham145/StudyNotion?style=for-the-badge&color=brightgreen" alt="License" />
</p>

<p align="center">
  <strong>Live Demo:</strong> 🔗 [your-frontend-url-here]
</p>

---

## 🚀 Features

- **For Students:**  
  - Browse courses, view content, add to wishlist, purchase via cart checkout.  
  - View course materials: videos, docs, descriptions, and manage personal details.

- **For Instructors:**  
  - Dashboard with course overview, ratings, analytics.  
  - Create, update, and delete courses and modules.  
  - Profile settings and insights access.

- **Back-end Highlights:**  
  - Auth via email, password, OTP, JWT.  
  - Razorpay integration for payments.  
  - Cloudinary for media handling, MongoDB for data storage.

---

## ⚙️ Tech Stack

| Front-end     | Back-end           | Database   | Authentication | Payments    | Media Storage |
|---------------|--------------------|------------|----------------|-------------|----------------|
| React.js      | Node.js + Express  | MongoDB    | JWT, OTP       | Razorpay    | Cloudinary     |


## 📸 Screenshots

> Replace these with your actual `assets/screenshots/*.png` files

### 🏠 Homepage



![Homepage](assets/screenshots/homepage.png)


### 📚 Course Catalog



![Course List](assets/screenshots/course-list.png)



### 👨‍🏫 Instructor Dashboard



![Instructor Dashboard](assets/screenshots/instructor-dashboard.png)



---

## 🛠️ Getting Started

### Prerequisites

- Node.js & npm  
- MongoDB instance or Atlas  
- Accounts & API keys: Gmail SMTP, Razorpay, Cloudinary

### Installation


git clone https://github.com/pratham145/StudyNotion.git
cd StudyNotion
npm install         # installs root (frontend) dependencies
cd server
npm install         # installs backend dependencies
cd ..


Create and configure:

* /server/.env:

  
  MONGODB_URL=...
  JWT_SECRET=...
  MAIL_HOST=smtp.gmail.com
  MAIL_PORT=...
  MAIL_USER=...
  MAIL_PASS=...
  RAZORPAY_KEY=...
  RAZORPAY_SECRET=...
  CLOUD_NAME=...
  CLOUD_API_KEY=...
  CLOUD_API_SECRET=...
  

* /.env (root):

  
  REACT_APP_BASE_URL=http://localhost:4000
  

### Running Locally

Launch both servers concurrently:


npm run dev  # concurrently starts frontend & backend


Frontend: `http://localhost:3000`
Backend APIs: `http://localhost:4000/api/...`

---

## 🧭 API Endpoints (abridged)

* `POST /api/auth/sendotp` – Send OTP
* `POST /api/auth/signup`
* `POST /api/auth/login`
* `GET/POST/PUT/DELETE /api/courses` – Course CRuD
* `POST /api/courses/:id/rate` – Submit rating

---

## 🚀 Deployment

* Frontend: [Vercel](https://vercel.com)
* Backend: [Railway](https://railway.app) / [Render](https://render.com)
* MongoDB: Atlas
* Media: Cloudinary

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/XYZ`)
3. Commit (`git commit -m "Add feature"`)
4. Push (`git push origin feature/XYZ`)
5. Open a Pull Request — **Hacktoberfest welcome!**

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## ✉️ Contact

* **Your Name** – Email: [you@example.com](mailto:you@example.com)
* GitHub: [pratham145](https://github.com/pratham145)

---

Made with ❤️ by **You**, for learners and instructors worldwide.





