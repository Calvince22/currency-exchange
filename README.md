# Currency Converter Website App

This is a single-page web application that allows users to convert currencies, keep a history of conversions, and edit or delete entries. The app fetches live exchange rates from the [ExchangeRate-API](https://www.exchangerate-api.com/).

## Features

- **Currency Conversion**: Select currencies and input an amount to convert between them.
- **Conversion History**: Displays a list of previous conversions.
- **CRUD Functionalities**:
  - **Add**: New conversions are automatically added to the history.
  - **Edit**: Modify existing conversions by pre-filling the input fields.
  - **Delete**: Remove individual conversions from the history.
  - **Clear All**: Double-click on the history section to clear all entries.
- **Real-Time Input Validation**: Validates the amount field as the user types.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling for a user-friendly interface.
- **JavaScript**: Logic and interactivity.
- **ExchangeRate-API**: Fetching live currency rates.

## How to Use

1. Open the app in a browser.
2. Select the currencies for conversion using the dropdown menus.
3. Enter an amount to convert.
4. Click the `Convert` button to see the result.
5. View and manage your conversion history:
   - Click `Edit` to modify an entry.
   - Click `Delete` to remove an entry.
   - Double-click the history section to clear all entries.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/calvince22/currency-converter.git
   ```
2. Open the `index.html` file in a browser.

## File Structure

```
.
├── index.html    # HTML structure
├── style.css     # CSS for styling
├── script.js     # JavaScript for functionality
└── README.md     # Documentation
```

## Event Listeners

The app uses the following distinct event listeners:

1. **`click`**: Triggered by the `Convert` button to calculate and display conversion results.
2. **`input`**: Validates the amount field as the user types and provides real-time feedback.
3. **`dblclick`**: Clears the entire conversion history when double-clicking the history section.

## Array Iteration

The app utilizes the `forEach` method to populate dropdown menus with currency options fetched from the API.

## Live Demo

[View the live demo here](https://calvince22.github.io/currency-exchange/) 

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [ExchangeRate-API](https://www.exchangerate-api.com/) for providing exchange rate data.
- Inspiration from currency conversion apps.

---

