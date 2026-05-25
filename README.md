<div align="center">

# 🕋 Arafah Duas  
### أدعية يوم عرفة

**A peaceful, elegant, and fully static web experience for reading Qur’anic duas, prophetic supplications, and authentic adhkar on the Day of Arafah.**

**تجربة ويب روحانية، أنيقة، وخفيفة لقراءة أدعية يوم عرفة من القرآن والسنة والأذكار الجامعة.**

<br />

![Arafah Duas Banner](./assets/preview.png)

<br />

[![Made with HTML](https://img.shields.io/badge/HTML-Static-orange?style=for-the-badge&logo=html5)](#)
[![Made with CSS](https://img.shields.io/badge/CSS-Responsive-blue?style=for-the-badge&logo=css3)](#)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-Interactive-yellow?style=for-the-badge&logo=javascript)](#)
[![No Backend](https://img.shields.io/badge/Backend-Not%20Required-lightgrey?style=for-the-badge)](#)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-black?style=for-the-badge&logo=github)](#)

<br />

[Live Demo](https://SultAlfaifi.github.io/arafah-duas) · [Report Issue](../../issues) · [Request Feature](../../issues)

</div>

---

## ✦ English Overview

**Arafah Duas** is a refined static web app designed to help users read, reflect, and spend meaningful time in dua on the blessed Day of Arafah.

The experience is built around a smooth card-based reading flow. Each dua appears inside a clean, full-width card, while progress is saved automatically in the browser. The app also includes a reading timer, dark mode, local progress tracking, and educational sections about the virtues of Arafah and the etiquettes of dua.

The project is intentionally simple, private, and easy to host.  
No backend. No login. No database. No external server.

---

## ✦ نظرة عامة بالعربية

**أدعية يوم عرفة** هو موقع ويب بسيط وأنيق يساعد المستخدم على قراءة الأدعية والأذكار في يوم عرفة بطريقة منظمة، هادئة، ومريحة.

يعتمد الموقع على تجربة قراءة بالبطاقات، حيث يظهر كل دعاء داخل كرت مستقل بتصميم نظيف، مع حفظ التقدم تلقائيًا داخل المتصفح، واحتساب مدة الدعاء، ودعم الوضع الليلي، وإضافة أقسام توعوية عن فضل يوم عرفة وآداب الدعاء.

تم بناء المشروع ليكون خفيفًا وسهل النشر ويحترم خصوصية المستخدم.  
بدون باك إند، بدون تسجيل دخول، بدون قاعدة بيانات، وبدون أي خادم خارجي.

---

## ✨ Key Features | المميزات

| Feature | Description |
|---|---|
| 🃏 Card Reading Experience | Smooth stacked cards for reading duas one by one |
| ⏱️ Reading Timer | Tracks how long the user spends reading and making dua |
| 💾 Local Progress Saving | Saves progress automatically using LocalStorage |
| 🌙 Dark Mode | Elegant light and dark themes |
| 📱 Mobile First | Designed primarily for mobile reading |
| 🧭 RTL Support | Fully optimized for Arabic content |
| 🕋 Arafah Virtues | Modal section about the virtues of the Day of Arafah |
| 🤲 Dua Etiquettes | Modal section for sunnah and etiquettes of dua |
| 🔐 Privacy Friendly | No accounts, no tracking, no external database |
| 🚀 GitHub Pages Ready | Can be deployed as a static website |

---

## 🧠 Experience Concept | فكرة التجربة

The user opens the page and immediately starts a calm dua-reading journey.

As the user scrolls, each card feels like a completed moment of reflection.  
The current card moves away smoothly, the next dua appears elegantly, and the progress counter updates automatically.

The goal is not just to display text, but to create a focused and peaceful reading experience.

---

## 🖼️ Preview | معاينة

> Add your screenshots here after deployment.

```md
![Home Screen](./assets/home.png)
![Dua Card](./assets/card.png)
![Dark Mode](./assets/dark-mode.png)
```

---

## 📦 Tech Stack | التقنيات المستخدمة

This project is built with simple static technologies:

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **LocalStorage**
- **GitHub Pages**

No framework is required.

---

## 🗂️ Project Structure | هيكلة المشروع

```bash
arafah-duas/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── assets/
    ├── preview.png
    ├── home.png
    ├── card.png
    └── dark-mode.png
```

---

## 🕋 Content Categories | تصنيفات المحتوى

The duas are organized into clear categories:

| Category | Arabic |
|---|---|
| Qur’anic Duas | أدعية قرآنية |
| Prophetic Duas | أدعية نبوية |
| Dhikr & General Duas | أذكار وأدعية جامعة |

Each card may include:

- Dua text
- Category badge
- Progress number
- Source reference when available

---

## 💾 Local Storage | الحفظ المحلي

The app stores user progress locally inside the browser.

Possible LocalStorage keys:

```js
arafah_dua_progress
arafah_dua_read_count
arafah_dua_elapsed_time
arafah_dua_theme
```

This means the user can leave and come back later without losing progress.

All data stays on the user’s device.

---

## 🔐 Privacy | الخصوصية

This project does **not** collect personal data.

It does not use:

- User accounts
- Login systems
- Cookies for tracking
- External databases
- Analytics scripts
- Backend servers

All saved progress is stored locally in the browser only.

---

## 🚀 Deployment | النشر على GitHub Pages

You can deploy the project easily using GitHub Pages.

### 1. Create a Repository

Create a new repository on GitHub, for example:

```bash
arafah-duas
```

### 2. Upload Files

Upload the following files:

```bash
index.html
style.css
script.js
README.md
assets/
```

### 3. Enable GitHub Pages

Go to:

```text
Repository Settings → Pages
```

Then choose:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

Save, and GitHub will generate a public link for the website.

---

## 🧪 Run Locally | التشغيل المحلي

Because this is a static website, you can open it directly:

```bash
open index.html
```

Or use a simple local server:

```bash
npx serve
```

---

## 🤲 Islamic Content Note | تنبيه حول المحتوى الشرعي

The content includes selected duas from:

- The Qur’an
- Prophetic supplications
- General authentic adhkar

This website is designed to help organize reading and reflection.  
It does not restrict dua to specific wordings, and it does not imply that these selected duas are obligatory.

Users may make dua with these supplications or with any good dua they wish.

---

## 🛣️ Future Improvements | تحسينات مستقبلية

Potential improvements:

- Add search inside duas
- Add favorite duas
- Add share button for each dua
- Add font size controls
- Add audio recitation support
- Add offline PWA support
- Add export/share progress summary
- Add multiple reading modes

---

## 👤 Author | صاحب المشروع

<div align="center">

Made with care by  
**[@SultAlfaifi](https://x.com/SultAlfaifi)**

صنع بواسطة  
**[@SultAlfaifi](https://x.com/SultAlfaifi)**

</div>

---

## 📄 License | الترخيص

This project is available for personal, educational, and non-commercial use.

هذا المشروع متاح للاستخدام الشخصي والتعليمي وغير التجاري.

---

<div align="center">

### May Allah accept our duas and good deeds.  
### تقبّل الله منا ومنكم صالح الأعمال.

</div>
