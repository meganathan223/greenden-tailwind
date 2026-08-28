# Greenden 
## Tailwind CSS Multi-Page Website

A simple, fast, and fully responsive multi-page website built using **Tailwind CSS**. This project features a clean structure with a conversion-ready landing page, dedicated product showcase, and a functional contact portal.

## 🚀 Live Demo
👉 [https://meganathan223.github.io/greenden-tailwind/]

## 📁 Pages Included

*   **🏠 Home / Landing Page:** Features a bold hero section, value propositions, and an action-focused CTA.
*   **📦 Products:** A responsive grid layout showcasing available items with hover effects.
*   **✉️ Contact:** A clean, accessible user inquiry form with styled inputs.

## 🛠️ Tech Stack

*   **HTML5:** Structured semantic markup.
*   **Tailwind CSS:** Utility-first CSS styling framework.

## 🚀 How to Run Locally

### 1. Clone the Project
```bash
git clone <your-repository-url>
cd <project-directory-name>
```

### 2. Install Tailwind CSS Dependencies
```bash
npm install -D tailwindcss
npx tailwindcss init
```

### 3. Start the Compilation Watcher
Run this command in your terminal to automatically build and compile your styles whenever you update your code:
```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

### 4. Launch the App
Open your web browser and launch your target root template folder file (e.g., `index.html`) to see the website live!

## 📱 Responsive Layout Rules
The project is built mobile-first. Responsive views switch layout parameters using native Tailwind breakpoints:
*   `sm:` Small screens (Phones)
*   `md:` Medium screens (Tablets)
*   `lg:` Large screens (Desktops)
