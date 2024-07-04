
# CryptoPlace Web App

CryptoPlace is a React web application built with Vite that allows users to explore and track cryptocurrencies. It provides real-time prices, market data, detailed cryptocurrency information, and more.

## Features

- **Top 10 Cryptocurrencies**: View the top 10 cryptocurrencies, their current price, 24-hour change, and market cap.
- **Search Functionality**: Search for any cryptocurrency and get real-time price updates.
- **Detailed Cryptocurrency Page**: Access detailed information for each cryptocurrency, including a price chart and other relevant data.
- **Currency Conversion**: Convert prices between different currencies.
- **Responsive Design**: The app is fully responsive and works on all device sizes.

## Project Structure

```
public
  └── vite.svg
src
  ├── assets
  ├── components
  │   ├── Footer
  │   │   ├── Footer.jsx
  │   │   └── Footer.css
  │   ├── LineChart
  │   │   └── LineChart.jsx
  │   ├── Navbar
  │       ├── Navbar.jsx
  │       └── Navbar.css
  ├── context
  │   └── CoinContext.jsx
  ├── Pages
  │   ├── Coin
  │   │   ├── Coin.jsx
  │   │   └── Coin.css
  │   └── Home
  │       ├── Home.jsx
  │       └── Home.css
  ├── app.jsx
  ├── index.css
  ├── main.jsx
.eslintrc.cjs
.gitignore
index.html
package-lock.json
package.json
readme.md
vite.config.js
```

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/cryptotracker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd cryptotracker
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

1. Open your browser and navigate to `http://localhost:3000`.
2. Explore the top 10 cryptocurrencies on the homepage.
3. Use the search bar to find any cryptocurrency and view its details.
4. Click on a cryptocurrency to see detailed information and a price chart.
5. Use the currency conversion feature to convert prices between different currencies.

## Technologies Used

- **ReactJS**
- **Vite**
- **CoinGecko API**
- **react-dom**
- **react-router-dom**
- **react-google-chart**
- **CSS**

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Gulam Quadir Parwez - [gulamquadir500@gmail.com]

Project Link: [https://github.com/gulamquadir500/CryptoPlace](https://github.com/gulamquadir500/CryptoPlace)
```
