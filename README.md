# Crypto Tracker App

A React Native mobile application for tracking cryptocurrency prices, managing your portfolio, and creating watchlists.

![Crypto Tracker](assets/icon.png)

## Features

- **Real-time cryptocurrency data**: View up-to-date prices, market caps, and percentage changes
- **Detailed coin information**: Access comprehensive data on individual cryptocurrencies
- **Price charts**: Interactive line and candlestick charts for price analysis
- **Portfolio management**: Track your crypto investments and performance
- **Watchlist**: Save your favorite cryptocurrencies for quick access
- **Currency converter**: Convert between cryptocurrencies and USD

## Screenshots

The app includes multiple screens:

- Home screen showing list of cryptocurrencies
- Detailed coin information with price charts
- Portfolio screen to track your investments
- Watchlist screen for quick access to favorite coins

## Technologies Used

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- [Axios](https://axios-http.com/) for API requests
- [React Native Charts](https://github.com/rainbow-me/react-native-animated-charts) for data visualization
- [Recoil](https://recoiljs.org/) for state management
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) for local data persistence

## API

This application uses the [CoinGecko API](https://www.coingecko.com/en/api) for cryptocurrency data, including:

- Current market prices
- Historical price data
- Detailed coin information
- Market cap rankings

## Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/crypto-tracker.git
cd crypto-tracker
```

2. Install dependencies
```bash
npm install
```

3. Start the Expo development server
```bash
npm start
```

4. Open the app on your device or emulator
   - Use the Expo Go app on your phone
   - Press 'a' for Android emulator
   - Press 'i' for iOS simulator

## Usage

### Home Screen
Browse through a list of cryptocurrencies sorted by market cap. Pull down to refresh data.

### Coin Details
Tap on any cryptocurrency to view detailed information, including:
- Current price and price changes
- Interactive price charts (line and candlestick)
- Currency converter

### Portfolio
- Track your crypto investments
- Add new assets to your portfolio
- View total portfolio value and performance

### Watchlist
- Add/remove coins to your watchlist
- Quickly access your favorite cryptocurrencies

## Project Structure

```
crypto-tracker/
├── assets/               # Images, fonts, and data
├── src/
│   ├── atoms/           # Recoil atoms for state management
│   ├── components/      # Reusable components
│   ├── contexts/        # React context providers
│   ├── navigation/      # Navigation configuration
│   ├── screens/         # App screens
│   └── services/        # API services
├── App.js               # Main application component
└── package.json         # Project dependencies
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Data provided by [CoinGecko](https://www.coingecko.com/)
- Icons from [Expo Vector Icons](https://icons.expo.fyi/)

Similar code found with 1 license type
