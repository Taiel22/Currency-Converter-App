# 💱 Currency Converter App

A simple and interactive currency converter built using **HTML, CSS, and JavaScript**. This project allows users to convert an amount from one currency to another using exchange rates fetched from the ExchangeRate-API.

## ✨ Features

- **Real-Time Exchange Rates:** Fetches currency exchange rate data from an external API.
- **Multiple Currencies:** Dynamically populates currency dropdown menus using the currencies returned by the API.
- **Easy Conversion:** Enter an amount, select the source and target currencies, and click the Convert button.
- **Instant Results:** Displays the converted amount with two decimal places.
- **Dark Theme:** Features a modern dark interface with blue accents.
- **Responsive Layout:** Uses a centered layout designed to fit different screen sizes.
- **Interactive UI:** Includes styled input fields, dropdown menus, and hover effects.

## 🛠️ Technologies Used

- **HTML5** – Structures the application and conversion form.
- **CSS3** – Provides styling, layout, colors, and interactive effects.
- **JavaScript (ES6+)** – Handles user input, API requests, and currency conversion.
- **ExchangeRate-API** – Supplies currency exchange rate data.
- **Google Fonts (Poppins)** – Enhances the application's typography.

## 📂 Project Structure

```text
currency-converter/
│
├── index.html       # Application structure
├── style.css        # Styling and layout
├── script.js        # Currency fetching and conversion logic
└── README.md        # Project documentation
```

## 🚀 Getting Started

### 1. Clone the Repository

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY` with your GitHub username and repository name.

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Open the Project

Navigate to the project folder:

```bash
cd YOUR_REPOSITORY
```

### 3. Run the Application

Open `index.html` in your web browser.

For the best development experience, you can also open the project folder in Visual Studio Code and use the Live Server extension.

**Note:** An active internet connection is required to load the currency exchange data from the API and the Poppins font from Google Fonts.

## 💡 How It Works

1. When the application loads, JavaScript sends a request to the ExchangeRate-API to retrieve currency exchange rates.
2. The available currency codes are extracted from the API response.
3. The currency dropdown menus are populated dynamically.
4. The user enters an amount and selects the source and target currencies.
5. When the Convert button is clicked, the application fetches exchange rates for the selected source currency.
6. The entered amount is multiplied by the exchange rate for the target currency.
7. The converted result is displayed on the page, formatted to two decimal places.

## 🌐 API Used

This project uses the ExchangeRate-API's latest-rates endpoint.

**Base currency endpoint:**

```text
https://api.exchangerate-api.com/v4/latest/USD
```

The application also requests rates for the selected source currency.

The API provides the exchange rate data used in the conversion calculations. Rates may change over time.

## 🎨 Design Highlights

- Dark navy background for a clean, modern appearance.
- Contrasting blue buttons for the primary action.
- Rounded form elements and a card-style container.
- Consistent spacing and readable typography.
- Hover and focus effects for better interaction feedback.

## 📚 What I Learned

Building this project helped me practise:

- Structuring web applications with HTML.
- Styling interfaces using CSS variables and Flexbox.
- Selecting and updating DOM elements with JavaScript.
- Handling form submissions and user input.
- Making asynchronous API requests using `async/await` and `fetch()`.
- Working with JSON responses and dynamically creating dropdown options.
- Performing calculations and formatting numeric results.

## 🔮 Future Improvements

- Add loading indicators while fetching exchange rates.
- Handle API errors and network failures gracefully.
- Validate amounts to prevent invalid or empty conversions.
- Add a currency swap button.
- Display the exchange rate used for each conversion.
- Add currency names and country flags.
- Improve accessibility and mobile responsiveness.
- Cache exchange rates to reduce unnecessary API requests.
- Add automated tests for the conversion logic.

## 👨‍💻 Author

**Taiel**

GitHub: [Visit My GitHub Profile](https://github.com/Taiel22)

---

⭐ If you find this project useful, consider giving the repository a star!
