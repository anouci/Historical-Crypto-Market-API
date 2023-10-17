# Historical Crypto-Market Analyzer 📜📊

Dive deep into historical liquidity, volume, price, and market cap trends for any crypto asset, empowering you to understand its past performance and forecast future trajectories.

![Mobula Logo](https://i.imgur.com/YI8M066.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Quick Guide](#quick-guide-)
- [API Reference](#api-reference-)

---

## Features ✨

- **Comprehensive Data Views:** Get a holistic view of any asset's history.
- **Interactive Graphs:** Visualize trends through interactive time-based charts.
- **Compare and Contrast:** Analyze multiple assets simultaneously for better investment decisions.
- **Downloadable Reports:** Generate detailed reports for offline analysis.

---

## Usage 💡

Ideal for investors, researchers, and enthusiasts, this analyzer provides a comprehensive lens into the historical performance of crypto assets. Decipher patterns, understand growth trajectories, and make well-informed decisions.

---

## Quick Guide 🚀

### Building with [Node.js](https://nodejs.org/) and [Chart.js](https://www.chartjs.org/):

1. **Initiate a Node.js Project:**
   - Download and install [Node.js](https://nodejs.org/) and npm.
   - Start a new project:
     ```bash
     npm init -y
     ```

2. **Fetching Historical Data:**
   - Use the Mobula API to fetch historical market data for desired assets.
   - Consider using [axios](https://github.com/axios/axios) or another HTTP client for API requests.

3. **Visualizing Data:**
   - Implement interactive charts with [Chart.js](https://www.chartjs.org/) to showcase historical trends.
   - Display liquidity, volume, price, and market cap data in user-friendly formats, possibly in tabulated sections or multi-line graphs for comparative analysis.

4. **Data Export Options:**
   - Integrate functionalities that allow users to download the visualized data as reports, in formats like PDF or CSV.

---

## API Reference 🌐

The primary endpoint used for the Historical Crypto-Market Analyzer:

- **Crypto-asset historical market data:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/market/history`
  - **Details:** Acquire the historical liquidity, volume, price, and market cap data for crypto assets.

Dive into the [Mobula API documentation](https://developer.mobula.fi/reference/getmarkethistory) for a comprehensive understanding.

---

Empowering you with a deeper understanding of the crypto world, using the [Mobula API](https://developer.mobula.fi/). 

Crafted with ❤️
