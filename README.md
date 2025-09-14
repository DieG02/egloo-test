# 🥚 Egloo Test

> This is my submission for the Egloo Frontend Developer test.

---

## 🚀 Live Demo

You can view the live demo of the project here:

[https://egloo-test.netlify.app/](https://egloo-test.netlify.app/)

---

## 📦 Project Structure

The project is built with **Astro** and uses a modular folder structure to maintain organization.



```
egloo-test/
├── node_modules/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   │   └── index.astro
│   ├── styles/
│   └── utils/
│       └── source.json
├── .gitignore
├── astro.config.mjs
├── package.json
└── README.md
```

---

## 🛠️ Technologies Used

-   **Astro:** The core framework for building the site.
-   **Lucide Icons:** A simple, beautiful, and consistent icon library.

---

## ✨ Features

-   **Component-based architecture:** The UI is broken down into reusable components for easy maintenance and scalability.
-   **Data handling:** Data is fetched from a mock `source.json` file located in the `src/utils` directory.
-   **CSS Styling:** All styling is managed within the `src/styles` folder for a clean separation of concerns.

---

## 💻 Installation and Usage

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/DieG02/egloo-test/
    cd egloo-test
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```

    This will start a local server, and you can view the project at `http://localhost:4321`.

4.  **Build for production:**
    ```bash
    npm run build
    ```

    This will generate the production-ready files in the `dist` folder.
