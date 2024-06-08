# Currency Converter

A web application for converting currency values from one type to another. This app allows users to input an amount in one currency, select the target currency, and get the converted amount instantly. Users can also swap the currencies with a single click.

## Features

- Real-time currency conversion based on the latest exchange rates.
- Swap currencies functionality to quickly reverse the conversion direction.
- User-friendly interface with input validation.
- Beautiful background image with a slightly blurred container for inputs.
- Responsive design for seamless use on various devices.

## Screenshots

![Screenshot](https://drive.google.com/uc?export=view&id=12optRMk4wLa7HcFkqc_AtFi6dpTOw-OP)

## Tech Stack

- **React**: Frontend library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **JavaScript**: Programming language for implementing logic.
- **Currency API**: Used for fetching the latest exchange rates.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/currency-converter.git
    ```

2. Navigate to the project directory:
    ```sh
    cd currency-converter
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm run dev
    ```

## Usage

1. Enter the amount you want to convert in the "From" section.
2. Select the currency type for the "From" section.
3. Select the target currency type in the "To" section.
4. Click the "Convert" button to get the converted amount.
5. Use the "Swap" button to swap the currencies.

## Components

### App Component

The main component handles the state and logic for currency conversion. It includes:

- State management for amount, from currency, to currency, and converted amount.
- Functions to handle currency swapping and conversion.
- JSX structure for rendering the input fields, swap button, and conversion result.

### InputBox Component

A reusable component for input fields and dropdowns. It includes:

- Props for label, amount, onAmountChange, onCurrencyChange, currencyOptions, selectCurrency, amountDisable, currencyDisable, and className.
- JSX structure for rendering the input field and dropdown menu.

### useCurrencyInfo Hook

A custom hook to fetch currency exchange rates. It includes:

- State management for fetched data.
- useEffect hook to fetch data from the Currency API whenever the `from` currency changes.

## Acknowledgements

- [Fawaz Ahmed](https://github.com/fawazahmed0/currency-api) for the Currency API.
- [Tailwind CSS](https://tailwindcss.com/) for the CSS framework.
- [React](https://reactjs.org/) for the JavaScript library.

## Contact

For any inquiries or feedback, feel free to contact me at [yatendra1456@gmail.com].
