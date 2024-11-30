# Currency Converter

A simple and interactive web application to convert currencies in real time using exchange rates fetched from an external API. The app displays the selected currencies' flags for a visually appealing user experience.

---

## Features
- Convert currencies using up-to-date exchange rates.
- Select currencies from dropdown menus with flags for better identification.
- Automatically updates exchange rates when currencies are changed.
- Pre-selected defaults: **USD** to **INR** for quick conversion.

---

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/CurrencyConverter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CurrencyConverter
   ```
3. Open the `index.html` file in your web browser:
   - You can use any browser to view the app (no server setup is required).

---

## Usage

1. Enter the amount you wish to convert in the **"Enter Amount"** field.
2. Select the **"From"** and **"To"** currencies from the dropdown menus.
3. Click the **"Get Exchange Rate"** button to view the converted value.
4. The app will fetch the latest exchange rate and display it below the dropdowns.

---

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the user interface.
- **JavaScript**: For functionality and API integration.
- **Currency API**: [Currency API](https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api) for real-time exchange rates.
- **Flags API**: [Flags API](https://flagsapi.com) for displaying currency flags.

---

## Folder Structure

```
CurrencyConverter/
│
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
├── app.js           # Main JavaScript logic for the app
├── code.js          # Data containing country codes and currencies
└── README.md        # Project documentation (this file)
```

---

## Contributing

We welcome contributions! Here's how you can help:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your fork:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---


Feel free to let me know if you’d like to add any specific sections or more details!
