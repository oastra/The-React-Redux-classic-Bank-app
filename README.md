# The React-Redux Bank

The React-Redux Bank is a simulated banking application built with React and Redux. It allows users to manage a customer profile and perform basic banking operations like deposits, withdrawals, and loan requests. The app also features currency conversion for deposits, utilizing an external API.

## Features

- **Customer Management**: Create a new customer profile with a full name and national ID.
- **Account Operations**: Perform deposits, withdrawals, and request loans with purpose tracking.
- **Currency Conversion**: Convert deposit amounts from various currencies to USD.
- **Balance Display**: Shows the current balance in USD.
- **Loan Management**: Request and pay back loans, with loan amount and purpose tracking.

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/react-redux-bank.git
   ```

   Replace your-username with your GitHub username.

2. **Navigate to the project directory**:

`cd react-redux-bank`

3. **Install dependencies**:

`npm install`

### Running the Project

To start the development server, use:

`npm start`
The app will run on http://localhost:3000.

## Available Scripts

In the project directory, you can run:

`npm start`: Runs the app in development mode.
`npm run build` : Builds the app for production.
`npm test` : Launches the test runner.
`npm run eject` : Ejects the app from the default configuration, allowing custom setups.

## Project Structure

- **App.js**: Main component rendering customer info and account operations.
- **AccountOperations.js**: Handles deposits, withdrawals, and loan requests.
- **BalanceDisplay.js**: Displays the account balance in USD.
- **CreateCustomer.js**: Form for creating a new customer.
- **Customer.js**: Displays a welcome message for the customer.
- **store.js**: Configures the Redux store with middleware.
- **accountSlice.js**: Redux slice managing account actions.
- **customerSlice.js**: Redux slice managing customer actions.
- **index.js**: Entry point rendering the React app with Redux provider.
- **API Usage**
  Currency conversion in the deposit feature uses the Frankfurter API.

## Author

Olha Chernysh
# The-React-Redux-classic-Bank-app
