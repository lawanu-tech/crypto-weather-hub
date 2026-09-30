# 🌦️₿ Crypto Weather Hub

A modern web application that brings **cryptocurrency market data and weather information together in one dashboard**.

Crypto Weather Hub is designed as a clean, responsive dashboard for exploring real-time market information alongside weather conditions.

🔗 **Live Demo:** [https://crypto-weather-hub.vercel.app/](https://crypto-weather-hub.vercel.app/)

🔗 **GitHub Repository:** [https://github.com/lawanu-tech/crypto-weather-hub](https://github.com/lawanu-tech/crypto-weather-hub)

---

## ✨ Features

* ₿ **Cryptocurrency Dashboard**

  * View cryptocurrency market information
  * Track crypto prices and related market data
  * Clean and intuitive presentation of financial data

* 🌤️ **Weather Information**

  * View weather information in the dashboard
  * Easy-to-understand weather presentation
  * Designed for quick access to current conditions

* 📊 **Modern Dashboard UI**

  * Responsive layout
  * Clean and modern interface
  * Component-based architecture
  * Optimized for desktop and mobile screens

* ⚡ **Fast Development & Performance**

  * Powered by Vite
  * Fast development server
  * Optimized production builds

* 📱 **Responsive Design**

  * Desktop-friendly
  * Tablet support
  * Mobile-responsive interface

---

## 🛠️ Tech Stack

### Frontend

* **React**
* **TypeScript**
* **Vite**
* **Tailwind CSS**

### Development Tools

* ESLint
* PostCSS
* TypeScript
* Vite

### Deployment

* **Vercel**

---

## 📁 Project Structure

```text
crypto-weather-hub/
│
├── public/                 # Static assets
│
├── src/                    # Application source code
│   ├── components/         # Reusable UI components
│   ├── pages/              # Application pages
│   ├── App.tsx             # Main application component
│   ├── main.tsx            # Application entry point
│   └── ...
│
├── .gitignore
├── components.json
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
├── vercel.json
└── vite.config.ts
```

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/lawanu-tech/crypto-weather-hub.git
```

### 2. Navigate to the project

```bash
cd crypto-weather-hub
```

### 3. Install dependencies

Using npm:

```bash
npm install
```

Or, if you use Bun:

```bash
bun install
```

### 4. Start the development server

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

### 5. Create a production build

```bash
npm run build
```

### 6. Preview the production build

```bash
npm run preview
```

---

## 🔧 Environment Variables

If your project uses external APIs, create a `.env` file in the root directory and add the required API configuration.

Example:

```env
VITE_WEATHER_API_KEY=your_weather_api_key
VITE_CRYPTO_API_KEY=your_crypto_api_key
```

> **Note:** Never commit API keys, passwords, tokens, or other secrets to GitHub.

If an API does not require a key, no environment variable is necessary.

---

## 📊 How It Works

The application follows a simple dashboard architecture:

```text
                 ┌─────────────────────┐
                 │     User / Browser  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │    React Frontend   │
                 │     + TypeScript    │
                 └──────────┬──────────┘
                            │
              ┌─────────────┴─────────────┐
              │                           │
              ▼                           ▼
     ┌─────────────────┐        ┌─────────────────┐
     │ Crypto Data API │        │  Weather API    │
     └─────────────────┘        └─────────────────┘
              │                           │
              └─────────────┬─────────────┘
                            ▼
                 ┌─────────────────────┐
                 │   Dashboard UI      │
                 │  Crypto + Weather   │
                 └─────────────────────┘
```

---

## 🎯 Project Goals

The main goals of Crypto Weather Hub are:

* Practice building a modern React application
* Work with external APIs
* Display dynamic data in a user-friendly dashboard
* Build reusable React components
* Implement responsive UI design
* Work with TypeScript
* Learn modern frontend development using Vite
* Deploy a production-ready frontend application

---

## 💡 Future Improvements

Potential improvements for future versions include:

* [ ] Add cryptocurrency search
* [ ] Add cryptocurrency price charts
* [ ] Add historical market data
* [ ] Add multiple cryptocurrency support
* [ ] Add city/location search for weather
* [ ] Add 7-day weather forecast
* [ ] Add cryptocurrency watchlist
* [ ] Add dark/light theme
* [ ] Add price-change notifications
* [ ] Add more detailed market statistics
* [ ] Add loading states and skeleton screens
* [ ] Improve accessibility
* [ ] Add automated tests

---

## 🤝 Contributing

Contributions are welcome.

### Fork the repository

```bash
git fork https://github.com/lawanu-tech/crypto-weather-hub.git
```

### Create a feature branch

```bash
git checkout -b feature/your-feature
```

### Make your changes

Commit your changes:

```bash
git add .
git commit -m "Add your feature"
```

### Push your branch

```bash
git push origin feature/your-feature
```

Then open a Pull Request.

---

## 🐛 Issues

If you find a bug or have a feature request, please open an issue in the GitHub repository.

---

## 📄 License

This project is currently available as an open-source project.

If you intend to distribute or reuse the project commercially, consider adding an appropriate license such as the MIT License.

---

## 👨‍💻 Author

**Lawanu Borthakur**

GitHub:
[https://github.com/lawanu-tech](https://github.com/lawanu-tech)

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Built with React, TypeScript, Vite and Tailwind CSS.**


