# 💬 Heart Me Out – Counselling Website  

![HTML](https://img.shields.io/badge/Frontend-HTML-orange)  
![CSS](https://img.shields.io/badge/Style-CSS-blue)  
![JavaScript](https://img.shields.io/badge/Scripting-JavaScript-yellow)  
![Vue](https://img.shields.io/badge/Framework-Vue.js-green)  
![PHP](https://img.shields.io/badge/Backend-PHP-lightgrey)  
![WebRTC](https://img.shields.io/badge/VideoCall-WebRTC-red)  

A web-based **open-source counselling platform** where users can connect with counsellors via chat, forms, and **direct video calls**. The platform ensures **privacy, empathy, and support** without collecting personal data.  

> **Who is this for?** Individuals seeking free counselling support, developers building healthcare tools, or learners showcasing a **full-stack web project** (HTML, CSS, JS, Vue, PHP, WebRTC).  

---

## 🧭 Table of Contents
- Overview  
- Key Features  
- Tech Stack  
- Project Structure  
- Setup  
- How to Run  
- Future Enhancements  
- Author  

---

## 🔎 Overview
**Heart Me Out** provides:  
- A safe space to share thoughts without judgment  
- Free counselling via **direct video calling** (powered by WebRTC)  
- Options to choose between counsellors and counselling types  
- Simple login system for access control  

All pages are static/dynamic HTML with styling in CSS, interactivity with **JavaScript & Vue.js**, and video call integration.  

---

## 🧩 Key Features
- 🏠 **Landing Page** with hero section & CTA buttons  
- ℹ️ **About Page** to explain the platform’s mission  
- 📩 **Feedback/Contact Form** with validation  
- 🔐 **Login Page** for secure entry before video sessions  
- 🎥 **Video Call (WebRTC)** for live counselling  
- 🧑‍⚕️ **Counsellor & Client Selection Pages** with guided choices  
- 🎨 Responsive & modern UI (CSS + animations)  

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Vue.js  
- **Backend:** PHP (for login/authentication)  
- **Video Calling:** WebRTC + Scaledrone  
- **UI Enhancements:** Custom JS (`front.js`, `special.js`)  

---

## 📂 Project Structure
```
Heart-Me-Out/
├── index.html        # Landing page (Vue integrated)
├── about.html        # About us page
├── feedback.html     # Contact/feedback form
├── login.html        # Login page (frontend validation)
├── login.php         # Login backend logic
├── video.html        # Video call page (WebRTC + Scaledrone)
├── s2.html           # Client counselling type selection
├── styles.css        # Main CSS styling
├── front.js          # Button hover/click effects
├── special.js        # Counsellor selection logic
└── (images, assets)
```

---

## ⚙️ Setup
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/heart-me-out.git
   cd heart-me-out
   ```
2. Place all files in your web server (e.g., **XAMPP/Apache**).  
3. Ensure PHP is enabled for `login.php`.  
4. Internet connection required for **WebRTC/Scaledrone video calls**.  

---

## ▶️ How to Run
1. Open `index.html` in a browser (or via localhost).  
2. Navigate:  
   - `About` → learn about the platform  
   - `Feedback` → send a message  
   - `Login` → access counsellor video session  
3. After login → redirects to `video.html` where **WebRTC live video counselling** starts.  

---

## 🧭 Future Enhancements
- ✅ Database integration (MySQL) for secure login & feedback storage  
- ✅ Real-time chat system alongside video calls  
- ✅ Admin dashboard for counsellor management  
- ✅ Mobile-first UI redesign  
- ✅ AI-powered chatbot for pre-counselling support  

---

## 👤 Author
**Ajay Singh**  
📧 <ajaysingh60970@gmail.com> • 🌐 [LinkedIn](https://www.linkedin.com/in/ajay-singh-28957035b/) • 💻 [GitHub](https://github.com/ajaysingh6097)  

If you found this useful, please ⭐ star the repo!  
