# 🌊 L'Océan Gourmet

**L'Océan Gourmet** is a high-end seafood restaurant web application that provides a premium digital dining experience. It features a modern, "dark luxury" interface where users can explore the daily catch, manage their cart, and place orders with real-time price calculations.

---

## ✨ Key Features

* **Dynamic Menu:** Loads the freshest seafood dishes directly from the [TheMealDB API](https://www.themealdb.com/).
* **Interactive Shopping Cart:** Real-time adding and removing of items with a persistent sidebar.
* **Smart Pricing:** Automatic subtotal calculation with an optional **10% Service Charge** toggle.
* **Premium UI/UX:** * Grayscale-to-color image transitions on hover.
    * Elegant typography using *Playfair Display* and *Poppins*.
    * Custom-built modal system for notifications and order confirmations.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Grid & Flexbox), JavaScript (ES6+)
* **Bundler:** [Vite](https://vitejs.dev/)
* **Fonts:** Google Fonts API
* **API:** TheMealDB (Seafood Category)

---

## 🚀 Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [[https://github.com/your-username/locean-gourmet.git](https://github.com/your-username/locean-gourmet.git)]](https://github.com/OlhaKhodakivska/L-Oc-an-Gourmet-.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd locean-gourmet
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the development server:**
    ```bash
    npm run dev
    ```

5.  **Build for production:**
    ```bash
    npm run build
    ```

---

## 📂 Project Structure

```text
├── src/
│   ├── main.js        # Core logic (API fetching, Cart management, Modals)
│   └── style.css      # Custom styling & animations
├── index.html         # Main entry point
└── package.json       # Project dependencies and scripts
