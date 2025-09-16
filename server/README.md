# 🌟 Kindergarten School Website

A full-stack web application for managing a **Kindergarten School**.  
It includes frontend pages for visitors (Home, About, Contact, Gallery, Fees, Enroll Now, Calendar) and a backend with **Node.js + Express + MongoDB** for managing admissions and contact forms.

---

## 🚀 Features

### 👩‍🏫 Frontend (Client)
- Home page with school introduction  
- About page describing the school  
- Gallery with images  
- Contact form  
- Admission / Enroll Now page  
- Calendar & Events page  
- Fees structure page  
- Admin panel & Login page  

### ⚙️ Backend (Server)
- Built using **Node.js + Express**  
- MongoDB database for storing:
  - Contact form submissions  
  - Admission requests  

---

## 📂 Project Structure

```
kindergarden/
├── client/                 # Frontend (static HTML + CSS + JS)
│   ├── home.html
│   ├── about.html
│   ├── contact.html
│   ├── login.html
│   ├── gallery.html
│   ├── fees.html
│   ├── calender.html
│   ├── Enroll now.html
│   └── img/               # Images & logo
│
├── models/                # Mongoose models (Contact, Admission)
├── server.js / app.js     # Express server
├── package.json           # Dependencies & scripts
└── README.md              # Documentation
```

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ORM)  

---

## ⚡ Installation & Setup

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/kindergarden.git
   cd kindergarden
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Configure environment variables  
   Create a `.env` file in the root folder:  
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. Run the server  
   ```bash
   npm start
   ```

5. Open the frontend  
   - Open `client/home.html` in your browser, OR  
   - Serve it via Express if already integrated  

---

## 📸 Screenshots

*(Add screenshots of your home page, about page, and admin panel here)*  

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.  

---

## 📜 License

This project is licensed under the **MIT License**.  

