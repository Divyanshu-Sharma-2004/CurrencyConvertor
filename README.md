# Currency Converter Web Application

This is a **Currency Converter** web application built using **HTML**, **CSS**, and **JavaScript**. The app allows users to convert amounts from one currency to another based on live exchange rates fetched from an API.

## Features:
- **Live Currency Conversion**: Fetches real-time exchange rates from the **Fawaz Ahmed Currency API**.
- **Dropdown Selection**: Users can select the source and target currencies from dropdown lists.
- **Dynamic Flag Updates**: The flags of the countries corresponding to the selected currencies are dynamically displayed.
- **Amount Conversion**: Users can input an amount and get the equivalent in the target currency.
- **User-Friendly Interface**: The application is designed with simplicity and ease of use in mind.

## How To Use:
1. **Select Currency**: From the dropdown menus, select the currencies you want to convert from (source currency) and to (target currency).
2. **Enter Amount**: Type the amount you want to convert.
3. **Get Conversion**: Press the **Convert** button to see the conversion result.
4. **Result Displayed**: The equivalent amount in the target currency will be displayed on the screen.

## How It Works:
- The app uses the **Fawaz Ahmed Currency API** to fetch live exchange rates.
- When a user selects a currency and enters an amount, the app fetches the conversion rate from the API.
- The app then calculates the converted amount and displays it to the user.
- The country flags corresponding to the selected currencies are dynamically updated based on the dropdown selections.

## Code Breakdown:
- **HTML**: Basic structure with dropdowns for selecting currencies, an input field for entering the amount, and a button to trigger the conversion.
- **CSS**: Styled elements for a clean, user-friendly interface.
- **JavaScript**: Handles the logic of fetching the currency exchange rates, performing the conversion, and updating the UI.

## Example:

1. **Currency Selection**:
   - From: USD (United States Dollar)
   - To: INR (Indian Rupee)

2. **Amount Input**:
   - Amount: 100 USD

3. **Conversion Result**:
   - 100 USD = 7,650.56 INR (example output based on live rates)
