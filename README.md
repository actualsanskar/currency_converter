# Currency Converter

This is a simple currency converter application built with React and Vite. It allows users to convert amounts between different currencies using real-time exchange rates.

## Features

- Convert amounts between various currencies.
- Swap the "From" and "To" currencies with a single click.
- Real-time exchange rate fetching.
- Responsive and visually appealing UI.

## Technologies Used

- React
- Vite
- TailwindCSS (for styling)
- Currency API (for exchange rates)

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
  ```bash
  cd 02_currencyConvertor
  ```
3. Install dependencies:
  ```bash
  npm install
  ```

Running the Application
To start the development server, run: `npm run dev`

The application will be available at https://currency-converter-eight-sand-57.vercel.app/

### Usage

- Enter the amount in the "From" field.
- Select the "From" and "To" currencies from the dropdown menus.
- Click the "Convert" button to see the converted amount.
- Use the "Swap" button to switch the "From" and "To" currencies.

### File Structure
- src/components/InputBox.jsx: A reusable component for input fields and dropdowns.
- src/hooks/useCurrencyInfo.js: A custom hook to fetch currency exchange rates.
- src/App.jsx: The main application logic and UI.
