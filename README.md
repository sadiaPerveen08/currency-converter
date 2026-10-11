# 💱 Currency Converter

A modern, responsive Currency Converter built with **HTML, CSS, and JavaScript**. Convert amounts between different currencies using exchange-rate data from a public API.

The project features a clean user interface, country flags, smooth animations, and interactive currency selection.

## ✨ Features

- **Currency Conversion:** Convert amounts between supported currencies.
- **Live Exchange Rates:** Fetch the latest available rates from a public currency API.
- **Country Flags:** Display flags based on the selected currency.
- **Dynamic Dropdowns:** Select from a wide range of currencies.
- **Responsive Design:** Works on desktop and mobile screens.
- **Modern UI:** Gradient backgrounds, rounded cards, and subtle shadows.
- **Smooth Animations:** Entrance animations, hover effects, and transitions.
- **Input Validation:** Prevent invalid or non-positive amounts.
- **Error Handling:** Display a message when exchange-rate requests fail.

## 🛠️ Technologies Used

- **HTML5** — Project structure
- **CSS3** — Styling, responsive layout, animations, and transitions
- **JavaScript (ES6+)** — Currency selection, API requests, and conversion logic
- **Currency API** — Exchange-rate data
- **Flags API** — Country flag images
- **Font Awesome** — Icons

## 📁 Project Structure

```text
Currency-Converter/
│
├── index.html    # Main HTML page
├── style.css     # Styling and animations
├── codes.js      # Currency and country code mapping
├── app.js        # Conversion logic and API integration
└── README.md     # Project documentation
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sadiaPerveen08/currency-converter
```


### 2. Open the project

Open the project folder in Visual Studio Code.

### 3. Run the application

Open `index.html` in your browser, or use the **Live Server** extension in VS Code.

No additional JavaScript packages are required.

## 🔌 APIs Used

### Currency Exchange API

Provides exchange-rate data for currency conversion.

```text
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.json
```

### Flags API

Displays country flags according to the selected currency.

```text
https://flagsapi.com/US/flat/64.png
```

The country code in the flag URL changes dynamically based on the selected currency.

## 🧠 How It Works

1. The user enters an amount.
2. The user selects the source and target currencies.
3. JavaScript fetches the exchange rates from the API.
4. The application retrieves the rate for the selected target currency.
5. The entered amount is multiplied by the exchange rate.
6. The converted amount is displayed on the page.

## ⚠️ Notes

- Exchange rates may change over time.
- The displayed rate may differ from rates offered by banks or money-transfer services.
- An internet connection is required to fetch exchange rates and load flag images.
- API availability and supported currencies may vary.

## 🎯 Learning Objectives

This project helped me practice:

- DOM manipulation
- JavaScript event listeners
- Fetch API and asynchronous programming
- Working with JSON data
- Error handling using `try...catch`
- Dynamic HTML element creation
- Responsive CSS design
- CSS animations and transitions

## 👩‍💻 Author

**Sadia Perveen**

A beginner-friendly frontend development project created to practice JavaScript and build practical web development skills.

---

⭐ If you find this project useful, consider giving the repository a star!
