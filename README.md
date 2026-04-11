<div align="center">
  <img src="https://github.com/user-attachments/assets/3127f784-6d83-4be5-ac3e-f0ee04cc0f52" alt="NexusHub Banner" width="100%">

  # 🎬 NexusHub — Local Course Library
  
  **Bring your offline courses to life with an organized, gamified, and elegant library.**

  [![GitHub license](https://img.shields.io/github/license/matheuspereirafx/nexushub?style=for-the-badge&color=blue)](https://github.com/matheuspereirafx/nexushub)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

  <p align="center">
    <a href="#-overview">Overview</a> •
    <a href="#-features">Features</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-how-to-use">How to Use</a> •
    <a href="#-author">Author</a>
  </p>
</div>

---

## ✨ What is NexusHub?
**NexusHub** was developed to overcome the limitations of outdated platforms that lack visual progress tracking. It is a video player focused on offline courses built with **Vanilla HTML**, with a strong focus on **UI/UX**.

With NexusHub, you transform your local files into a modern interface. Simply open the `index.html` file in your browser and import your folder — the system automatically organizes everything, saves your progress, and allows you to pick up exactly where you left off, **without needing a server or internet connection**.

---

## 🚀 Features

| Feature | Description |
| :--- | :--- |
| 📁 **Smart Import** | Automatically detects master folders with multiple courses or a single course with modules. |
| 🎯 **Progress Tracking** | Progress is saved to the browser's `localStorage` and persists between sessions. |
| 📊 **Visual Dashboard** | Cards featuring progress bars, total time, and completed lessons per course. |
| 🎬 **Integrated Player** | Tree-view playlist with smooth navigation and automatic lesson marking. |
| 🔍 **Library Filters** | Organize by: *All*, *Not Started*, *In Progress*, or *Completed*. |
| 🖱️ **Drag & Drop** | Drag folders directly into the window to add content instantly. |
| 💾 **Zero Dependencies** | Works 100% offline after the initial load. |

---

## 🛠️ Tech Stack

The project uses a stack focused on independence and performance:

* **HTML5:** Structure and File APIs (`File API`, `webkitdirectory`).
* **CSS3 & Tailwind CSS:** Modern styling and responsive layout via CDN.
* **JavaScript (ES6+):** Business logic, folder detection, and data persistence.
* **Google Fonts:** Selected typography (Syne + Inter).
* **localStorage:** Local database for saving your study progress.

---

## 🗂️ Supported Folder Structure

The system automatically recognizes these hierarchies:

### 1. Master Folder (Multiple Courses)
```text
📁 My Courses/
├── 📁 Python Course/
│   ├── 📁 Module 1/
│   │   ├── lesson01.mp4
│   │   └── lesson02.mp4
│   └── 📁 Module 2/
└── 📁 JavaScript Course/
```

### 2. Single Course
```text
📁 React Course/
├── 📁 01 - Introduction/
│   ├── lesson01.mp4
└── 📁 02 - Hooks/
```

---

## 📦 How to Use

1. **Download the project:**
   ```bash
   git clone [https://github.com/matheuspereirafx/nexushub.git](https://github.com/matheuspereirafx/nexushub.git)
   ```

2. **Open in browser:**
   Double-click the `index.html` file. No installation or local server (like Node or Apache) is required.

3. **Import your courses:**
   Drag your course folder into the window, or click **"Select Course Folder"** and choose the desired directory.

---

## 💡 Important Information

* **Persistence:** Progress is saved per browser. If you clear your cache or switch computers, your local progress will not be transferred as this is a 100% local application.
* **Browsers:** Recommended for use in **Chromium-based** browsers (Chrome, Edge, Brave) for full support of the directory reading API.

---

## 🤝 Contributing

Contributions are what make the open-source community an amazing place!
* 🍴 **Fork** the project.
* 🌿 Create a **Branch** for your feature (`git checkout -b feature/AmazingFeature`).
* 💾 **Commit** your changes (`git commit -m 'feat: add some amazing feature'`).
* 🚀 **Push** to the Branch (`git push origin feature/AmazingFeature`).
* 🔃 Open a **Pull Request**.

---

<div align="center">
  <p>Developed with ♥ by <a href="https://github.com/matheuspereirafx">Matheus Pereira</a></p>
  
  <p>
    <a href="https://github.com/matheuspereirafx">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>
