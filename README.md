
# 🌍 Higher Education Hub

Welcome to **Higher Education Hub**, a dynamic, all-in-one dashboard designed for **prospective international students**.  
This tool aggregates **live news**, **cost of living data**, **visa information**, and **user-submitted reviews** to provide a comprehensive overview of various study destinations worldwide.

---

## ✨ Live Demo  
🚀 **[Click Here to Explore](https://monish21072004.github.io/Live-Higher-Studies-News-/)**

---

## 🖼️ Screenshot  
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a4abd875-32ce-47d0-92a7-e90ef061bb45" />

---

## 🚀 Features  

- **Live News Feed**  
  Fetches the latest **international student news** for any country from Google News in **real-time**.

- **Global Alerts**  
  A dedicated section for **high-priority news** affecting students worldwide, such as **visa policy changes** or **tuition fee updates**.

- **Comprehensive Country Navigator**  
  An alphabetized, scrollable sidebar listing **140+ countries** for easy exploration.

- **Dynamic Multi-Card Layout**  
  A three-column layout to display multiple country info cards **simultaneously**, intelligently adjusting to screen space.

- **Cost & Visa Information**  
  Provides **estimated monthly living costs (excluding rent)** and quick snapshots of **visa and post-study work information**.

- **Public Review System**  
  Persistent user-submitted **reviews** for sharing and reading real student experiences.

- **Live Currency Conversion**  
  Convert estimated costs into **15+ world currencies** instantly.

- **Modern Animated UI**  
  A **futuristic interface** with frosted glass effects, smooth animations, and a **dynamic background**.

- **Fully Responsive**  
  Works seamlessly on **desktops, tablets, and mobile devices**.

---

## 💻 Tech Stack  

This project is built with modern and accessible web technologies.

### **Frontend**  
- HTML5  
- CSS3 + [Tailwind CSS](https://tailwindcss.com/)  
- Vanilla JavaScript (ES6+)

### **APIs & External Services**
- **[JSONBin.io](https://jsonbin.io/):** Free JSON database backend for the review system.  
- **[RSS2JSON](https://rss2json.com/):** Converts Google News RSS feeds into JSON.  
- **[Frankfurter.app](https://www.frankfurter.app/):** Live currency exchange rates.  
- **[FlagCDN](https://flagcdn.com/):** Country flag images.

---

## 🛠️ Setup and Configuration  

This is a **single-page application** — no build process needed!  
Simply open `index.html` in your browser.  
To unlock **all features**, follow these steps:

### **1. Add `numbeo_data.json`**
- Ensure you have a `numbeo_data.json` file in the **root directory**.  
- This file contains **cost of living index data** used by the app.

---

### **2. Configure JSONBin.io for the Review System**
The public review system requires a **free JSONBin.io account**.

#### Step-by-Step Guide:
1. **Create a JSONBin.io Account:**  
   Go to [JSONBin.io](https://jsonbin.io/) and sign up.

2. **Get Your API Key:**  
   - After logging in, go to your **Profile → API Keys**.
   - Copy your **Master Key** → this is your `JSONBIN_API_KEY`.

3. **Create a New Bin:**  
   - On the dashboard, click **Create Bin**.  
   - Paste this JSON structure:
     ```json
     {
       "reviews": []
     }
     ```
   - Click **Create Bin**.

4. **Get Your Bin ID:**  
   - Look at the **URL** in your browser after creating the bin:
     ```
     https://jsonbin.io/b/YOUR_BIN_ID
     ```
   - Copy the `YOUR_BIN_ID` part → this is your `JSONBIN_BIN_ID`.

5. **Update Your Project:**  
   - Open `index.html`.  
   - Find this section in the JavaScript code:
     ```js
     // --- JSONBIN.IO CONFIGURATION ---
     const JSONBIN_API_KEY = '...';
     const JSONBIN_BIN_ID = '...';
     ```

---

## 📂 File Structure

```
Live-Higher-Studies-News-/
│
├── index.html         # Main application file (HTML, CSS, JS combined)
├── numbeo_data.json   # Cost of living data
├── README.md          # Project documentation
└── assets/            # Images, icons, etc. (if needed)

```

---

## 🤝 Contributing
Contributions are always welcome!  
- Fork this repo
- Create a new branch (`feature/YourFeature`)
- Commit your changes
- Open a **Pull Request**

---

## 📜 License
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 🔗 Important Links
- **GitHub Repository:** [Live-Higher-Studies-News-](https://github.com/Monish21072004/Live-Higher-Studies-News-.git)  
- **Live Deployment:** [View App Here](https://monish21072004.github.io/Live-Higher-Studies-News-/)

